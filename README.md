# hiivmind-corpus-github

A Claude Code plugin marketplace providing comprehensive GitHub documentation corpus for AI-assisted development.

## What This Is

This is a **documentation corpus** - a pre-indexed collection of official GitHub documentation that enables Claude to accurately answer questions about GitHub features, APIs, and best practices. Instead of relying on training data or web searches, Claude can reference the actual documentation.

## Included Corpora

| Plugin | Files | Description |
|--------|-------|-------------|
| `hiivmind-corpus-github-docs` | 3,346 docs + GraphQL schema | Official GitHub documentation from [github/docs](https://github.com/github/docs) |

### Coverage

The corpus includes documentation for:

**Development & Automation**
- GitHub Actions (239 docs) - workflows, runners, CI/CD
- REST API (292 docs) - endpoints, authentication
- GraphQL API (27 docs + full schema) - queries, mutations, types
- GitHub Copilot (321 docs) - setup, usage, customization
- Webhooks (22 docs) - events, payloads
- GitHub Apps (115 docs) - OAuth, integrations

**Security**
- Code Security (443 docs) - CodeQL, secret scanning, GHAS
- Authentication (79 docs) - SSO, 2FA, PATs, SSH keys

**Repository Management**
- Repositories (127 docs) - settings, branches, releases
- Pull Requests (68 docs) - reviews, merging
- Issues (104 docs) - labels, milestones, projects
- Codespaces (97 docs) - cloud dev environments

**Organization & Enterprise**
- Organizations (166 docs) - teams, permissions
- Enterprise Admin (392 docs) - policies, management
- Billing (98 docs) - plans, usage

...and 20+ more sections covering GitHub Desktop, Packages, Pages, Sponsors, Education, and more.

## Installation

```bash
# Install via Claude Code
/plugin marketplace add https://github.com/hiivmind/hiivmind-corpus-github
```

## Usage

After installation, Claude automatically uses the corpus when you ask about GitHub topics:

```
"How do I set up a reusable workflow in GitHub Actions?"

"What's the GraphQL mutation to create an issue?"

"How do I configure branch protection rules?"

"What scopes does my GitHub App need for reading PRs?"

"How do I set up Copilot for my organization?"
```

### GraphQL Schema

The corpus includes the complete GitHub GraphQL schema (70k+ lines, 957 types). Claude uses Grep patterns to efficiently search it:

```
"Find the Repository type definition in the GraphQL schema"

"What fields are available on the PullRequest type?"

"Show me the CreateIssueInput input type"
```

## Architecture

```
hiivmind-corpus-github/
├── .claude-plugin/
│   ├── plugin.json           # Marketplace manifest
│   └── marketplace.json      # Plugin registry
│
└── hiivmind-corpus-github-docs/
    ├── .claude-plugin/plugin.json
    ├── skills/navigate/SKILL.md    # Navigation skill
    ├── data/
    │   ├── config.yaml             # Source configuration
    │   ├── index.md                # Master index
    │   ├── sections/               # Per-section indices
    │   │   ├── actions.md
    │   │   ├── rest.md
    │   │   ├── graphql.md
    │   │   └── ... (36 sections)
    │   └── uploads/
    │       └── graphql-schema/     # Local GraphQL schema
    └── .source/                    # Cloned docs (gitignored)
```

## Maintenance

This marketplace is managed by the `hiivmind-corpus` meta-plugin. Available maintenance skills:

| Skill | Purpose |
|-------|---------|
| `hiivmind-corpus-refresh` | Update index when upstream docs change |
| `hiivmind-corpus-enhance` | Add depth to specific topics |
| `hiivmind-corpus-add-source` | Add new documentation sources |

To refresh the corpus when GitHub docs update:
```
"Refresh the GitHub docs corpus from upstream"
```

## Requirements

- Claude Code with plugin support
- `hiivmind-corpus` meta-plugin (for maintenance operations)

## License

MIT
