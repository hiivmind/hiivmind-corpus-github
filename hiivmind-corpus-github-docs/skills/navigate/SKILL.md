---
name: hiivmind-corpus-github-docs-navigate
description: This skill answers questions about GitHub documentation including GitHub Actions, REST API, GraphQL API, GitHub Copilot, code security, repositories, workflows, and the gh CLI. Use when user asks about GitHub features, GitHub API usage, Actions workflows, or gh command line tool.
---

# GitHub Docs Navigator

Direct access to GitHub documentation covering Actions, Copilot, REST API, GraphQL, code security, repositories, and more.

**User request:** $ARGUMENTS

**Corpus location:** `${CLAUDE_PLUGIN_ROOT}`

---

## Navigation Process

1. **Search the indexes first** (see Index Search section below)
   - Extract key concepts from the question
   - Grep the index files for those terms
   - If matches found → use those entries directly
2. **If no search matches, navigate by section**:
   - Read the master index: `data/index.md` - contains section overview and GraphQL schema reference
   - Find the relevant section and read its section index: `data/sections/{section}.md`
3. **Parse path format**: `{source_id}:{relative_path}`
4. **Check for `⚡ GREP` marker** - if present, use Grep instead of Read (see Large Structured Files section)
5. **Look up source** in `data/config.yaml` by ID
6. **Get content** based on source type (see Source Access below)
7. **Answer** with citation to source and file path

---

## Index Search (Recommended First Step)

**Before reading sections sequentially, SEARCH the indexes for relevant terms.**

### Step 1: Extract Key Concepts

Analyze the user's question and extract:
- **Explicit terms**: Words directly used in the question
- **Synonyms**: Related terms (e.g., "filter" → also try "view", "query", "search")
- **Domain terms**: Technical concepts that might appear in docs (e.g., "tag" → also try "label", "field")

Example: "How do I filter GitHub projects by tag?"
- Explicit: `filter`, `projects`, `tag`
- Synonyms: `view`, `query`, `search`
- Domain: `label`, `field`, `custom field`

### Step 2: Search All Index Files

```bash
# Search for each term across all index files
grep -ri "filter" data/ --include="*.md"
grep -ri "tag" data/ --include="*.md"
```

**Tip:** Search for the most specific term first. If no matches, broaden to synonyms.

### Step 3: Use Search Results

If grep finds matches:
1. **Direct hit**: Entry description matches the question → use that path
2. **Related hit**: Entry is in the right area but doesn't directly answer → **GO TO STEP 4 IMMEDIATELY**
3. **No hit in index**: The topic may not be indexed → **GO TO STEP 4 IMMEDIATELY**

**IMPORTANT:** If you searched for "filter" and only found "Views & Layouts" without "filter" in the description, that's a **related hit, not a direct hit**. Stop and ask the user before exploring further.

### Step 4: Clarify Before Exploring (IMPORTANT!)

**STOP HERE if you only found related content, not a direct answer.**

Don't start exploring, guessing paths, or searching the source files. Instead, **use AskUserQuestion** to clarify:

**Present these options:**

1. **Clarify the request** - Maybe the question can be rephrased
   - "Could you rephrase your question? I searched for '{terms}' but found no matches."
   - Suggest alternative terms: "Did you mean '{synonym}' or '{related_term}'?"

2. **Show what's available** - Help the user find related content
   - "The closest sections I found are: {list nearby sections}"
   - "Would any of these help: {list related entries}?"

3. **Identify an index gap** - If the user confirms their request was valid
   - "This topic isn't covered in the current index."
   - Offer: "Would you like me to enhance the index for this topic?"

---

## Index Structure

This corpus uses a **hierarchical index**:

```
data/
├── index.md                    # Master index with section overview
└── sections/
    ├── actions.md              # GitHub Actions (239 docs)
    ├── copilot.md              # GitHub Copilot (321 docs)
    ├── rest.md                 # REST API (292 docs)
    ├── code-security.md        # Code Security (443 docs)
    └── ... (36 total sections)
```

**Navigation flow:**
1. Start with `data/index.md` to find the right section
2. Read `data/sections/{section}.md` for detailed entries
3. Access the actual doc via path format

---

## Path Format

Index entries use the format: `{source_id}:{relative_path}`

Examples:
- `docs:actions/index.md` - Git source
- `gh-cli-manual:gh_repo_create` - Generated-docs source
- `local:team-standards/coding-guidelines.md` - Local uploads

---

## Source Access

### Worked Example (IMPORTANT - Follow This Pattern!)

**Index entry found:** `docs:issues/planning-and-tracking-with-projects/customizing-views/index.md`

**Step 1 - Parse the path:**
- `source_id` = `docs` (everything before the colon)
- `relative_path` = `issues/planning-and-tracking-with-projects/customizing-views/index.md` (everything after the colon)

**Step 2 - Look up source in config.yaml:**
```yaml
sources:
  - id: docs
    type: git
    repo_owner: github
    repo_name: docs
    branch: main
    docs_root: content
```

**Step 3 - Construct the full path:**
- Local clone: `.source/docs/content/issues/planning-and-tracking-with-projects/customizing-views/index.md`
- GitHub URL: `https://raw.githubusercontent.com/github/docs/main/content/issues/planning-and-tracking-with-projects/customizing-views/index.md`

**CRITICAL:** The `relative_path` from the index is used EXACTLY as-is. NEVER invent or guess filenames!

### For git sources

**Step 1 - Check for local clone:**
Use Glob to check if `.source/{source_id}/` exists.

**Step 2a - If local clone exists (PREFERRED):**
Read directly from `.source/{source_id}/{docs_root}/{relative_path}` using the Read tool.
This is faster and works offline.

**Step 2b - If NO local clone exists (fallback only):**
Fetch from GitHub using the EXACT path from the index:
```
https://raw.githubusercontent.com/{repo_owner}/{repo_name}/{branch}/{docs_root}/{relative_path}
```

### For generated-docs sources

**Step 1 - Look up source in config.yaml:**
```yaml
sources:
  - id: gh-cli-manual
    type: generated-docs
    web_output:
      base_url: https://cli.github.com/manual
```

**Step 2 - Construct URL:**
```
{base_url}/{relative_path}
```
Example: `https://cli.github.com/manual/gh_repo_create`

**Step 3 - Fetch via WebFetch**

### For local sources

Read directly from: `data/uploads/{source_id}/{path}`

### For web sources

Read from cache: `.cache/web/{source_id}/{cached_file}`

If cache miss, look up the URL in `data/config.yaml` and fetch fresh content.

---

## Large Structured Files (schemas, specs, configs)

For large files like GraphQL schemas, OpenAPI specs, or JSON configs, **DO NOT read the entire file**. Use Grep to search precisely:

**GraphQL Schema patterns:**
```bash
# Find a type definition
grep -n "^type Repository " schema.graphql -A 30

# Find an input type
grep -n "^input CreateIssueInput " schema.graphql -A 20

# Find a mutation
grep -n "createIssue" schema.graphql -B 2 -A 15

# Find all fields returning a specific type
grep -n ": Repository" schema.graphql

# Find enum values
grep -n "^enum IssueState " schema.graphql -A 10
```

**When to use Grep vs Read:**
- File > 1000 lines → prefer Grep
- Looking for specific definition → Grep with `-A` context
- Need surrounding context → Grep with `-B` and `-A`
- Need to understand overall structure → Read first 100 lines, then Grep

---

## File Locations

- **Master Index**: `data/index.md` - section overview, GraphQL schema reference
- **Section Indices**: `data/sections/{section}.md` - detailed per-section entries
- **Config**: `data/config.yaml` (has sources array with per-source tracking)
- **Git sources**: `.source/{source_id}/` (cloned repos, gitignored)
- **Local sources**: `data/uploads/{source_id}/` (user-uploaded files)
- **Web cache**: `.cache/web/{source_id}/` (fetched web content, gitignored)

---

## Output

- Cite the source ID and file path for reference
- Include code examples from the docs
- Suggest related docs from the same index section
- Note source type and freshness warnings if relevant

---

## Corpus Maintenance

For corpus maintenance, use the parent plugin:

```
/hiivmind-corpus refresh github-docs     - Update index from upstream
/hiivmind-corpus enhance github-docs X   - Add depth to topic X
/hiivmind-corpus status github-docs      - Check corpus freshness
```

---

## Making Projects Aware of This Corpus

If you're working in a project that uses GitHub features but doesn't know about this corpus, you can add awareness to the project's CLAUDE.md.

**The `references/project-awareness.md` file** contains a ready-to-use snippet that can be added to any project's CLAUDE.md to make Claude aware of this corpus when working in that project.

### When to Suggest Injection

Suggest adding project awareness when:
- User is working in a project with GitHub Actions workflows
- User repeatedly asks GitHub API questions without invoking the corpus
- User says "I keep forgetting to use the docs"

---

## Example Sessions

### Documentation Question

**User:** "how do I use composite actions?"

1. Grep `data/sections/actions.md` for "composite"
2. Find entry like `docs:actions/sharing-automations/creating-actions/creating-a-composite-action.md`
3. Read from `.source/docs/content/actions/sharing-automations/creating-actions/creating-a-composite-action.md`
4. Answer with code examples and link to source

### GraphQL Query

**User:** "GraphQL query for repository collaborators"

1. Read `data/index.md` GraphQL reference section
2. Grep the schema for "collaborators"
3. Provide the query structure with field descriptions

---

## Notes

- This corpus has ~2400+ documents across 36 sections
- GraphQL schema is indexed for quick type/mutation lookup
- Section indexes are searchable - always grep before reading sequentially
- For large files (schemas, specs), use Grep with context flags, not full Read
