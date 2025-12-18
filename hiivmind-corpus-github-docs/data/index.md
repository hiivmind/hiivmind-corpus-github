# GitHub Documentation Corpus

> **Sources:** docs (github/docs), graphql-schema (local), gh-cli-manual (web)
> **Total:** 3,346 documentation files + GraphQL schema + gh CLI reference
> **Last updated:** 2025-12-18

This corpus provides comprehensive GitHub documentation. The index is organized by section, with detailed indices in `sections/`.

---

## Quick Reference

### GraphQL API Schema

- **GitHub GraphQL Schema** `graphql-schema:schema.docs.graphql` ⚡ GREP - Complete GitHub GraphQL API schema (70k lines, 957 types, 381 inputs, 237 enums). Search patterns:
  - Find type: `grep -n "^type {Name} " ... -A 50`
  - Find input: `grep -n "^input {Name} " ... -A 30`
  - Find enum: `grep -n "^enum {Name} " ... -A 20`
  - Find mutation: `grep -n "{mutationName}" ... -B 5 -A 30`
  - Find fields returning type: `grep -n ": {TypeName}" ...`

### GitHub CLI (gh) Command Reference

Web source from https://cli.github.com/manual - detailed command reference with flags, options, and examples.

**Commands by category:** (165 commands indexed)

| Category | Commands | Description |
|----------|----------|-------------|
| **auth** | login, logout, refresh, setup-git, status, switch, token | Authentication management |
| **pr** | checkout, checks, close, comment, create, diff, edit, list, lock, merge, ready, reopen, revert, review, status, unlock, update-branch, view | Pull request operations |
| **issue** | close, comment, create, delete, develop, edit, list, lock, pin, reopen, status, transfer, unlock, unpin, view | Issue management |
| **repo** | archive, clone, create, delete, edit, fork, list, rename, set-default, sync, unarchive, view | Repository operations |
| **workflow** | disable, enable, list, run, view | Workflow management |
| **run** | cancel, delete, download, list, rerun, view, watch | Workflow run operations |
| **release** | create, delete, download, edit, list, upload, view | Release management |
| **project** | close, copy, create, delete, edit, field-*, item-*, link, list, mark-template, unlink, view | GitHub Projects |
| **search** | code, commits, issues, prs, repos | Search functionality |
| **secret/variable** | delete, get, list, set | Secrets and environment variables |
| **gist** | clone, create, delete, edit, list, rename, view | Gist management |
| **extension** | browse, create, exec, install, list, remove, search, upgrade | CLI extensions |
| **codespace** | code, cp, create, delete, edit, jupyter, list, logs, ports, rebuild, ssh, stop, view | Codespaces |
| **config/alias** | clear-cache, delete, get, import, list, set | Configuration and aliases |

**To fetch command details:** Use WebFetch with URL pattern `https://cli.github.com/manual/gh_{command}_{subcommand}` (e.g., `gh_pr_create`)

---

## Section Index

### Development & Automation

| Section | Files | Description | Index |
|---------|-------|-------------|-------|
| **Actions** | 239 | Workflows, runners, reusable actions, CI/CD | → `sections/actions.md` |
| **Apps** | 115 | GitHub Apps, OAuth Apps, webhooks integration | → `sections/apps.md` |
| **REST API** | 292 | REST API endpoints, authentication, guides | → `sections/rest.md` |
| **GraphQL** | 27 | GraphQL API guides and reference | → `sections/graphql.md` |
| **Webhooks** | 22 | Webhook events, payloads, delivery | → `sections/webhooks.md` |
| **Copilot** | 321 | GitHub Copilot setup, usage, customization | → `sections/copilot.md` |
| **GitHub CLI** | 8 | gh command-line tool | → `sections/github-cli.md` |
| **GitHub Models** | 13 | AI models in GitHub | → `sections/github-models.md` |

### Security

| Section | Files | Description | Index |
|---------|-------|-------------|-------|
| **Code Security** | 443 | Code scanning, CodeQL, secret scanning, GHAS | → `sections/code-security.md` |
| **Authentication** | 79 | SSO, 2FA, PATs, SSH keys | → `sections/authentication.md` |

### Repository Management

| Section | Files | Description | Index |
|---------|-------|-------------|-------|
| **Repositories** | 127 | Repo settings, branches, releases, files | → `sections/repositories.md` |
| **Pull Requests** | 68 | PRs, reviews, merging, conflicts | → `sections/pull-requests.md` |
| **Issues** | 104 | Issues, labels, milestones, projects | → `sections/issues.md` |
| **Discussions** | 17 | Community discussions | → `sections/discussions.md` |
| **Pages** | 29 | GitHub Pages hosting | → `sections/pages.md` |
| **Packages** | 24 | GitHub Packages registry | → `sections/packages.md` |

### Organization & Enterprise

| Section | Files | Description | Index |
|---------|-------|-------------|-------|
| **Organizations** | 166 | Org management, teams, permissions | → `sections/organizations.md` |
| **Admin** | 392 | Enterprise administration, policies | → `sections/admin.md` |
| **Enterprise Onboarding** | 37 | Enterprise setup guides | → `sections/enterprise-onboarding.md` |
| **Billing** | 98 | Plans, usage, spending limits | → `sections/billing.md` |

### Getting Started & Learning

| Section | Files | Description | Index |
|---------|-------|-------------|-------|
| **Get Started** | 117 | Onboarding, quickstarts, tutorials | → `sections/get-started.md` |
| **Contributing** | 43 | Contributing to open source | → `sections/contributing.md` |
| **Education** | 52 | GitHub Education, Classroom | → `sections/education.md` |
| **Communities** | 43 | Building communities | → `sections/communities.md` |

### Tools & Environments

| Section | Files | Description | Index |
|---------|-------|-------------|-------|
| **Codespaces** | 97 | Cloud development environments | → `sections/codespaces.md` |
| **Desktop** | 50 | GitHub Desktop app | → `sections/desktop.md` |
| **Integrations** | 17 | Third-party integrations | → `sections/integrations.md` |

### Account & Settings

| Section | Files | Description | Index |
|---------|-------|-------------|-------|
| **Account and Profile** | 68 | User settings, profiles, notifications | → `sections/account-and-profile.md` |
| **Subscriptions and Notifications** | 24 | Notification settings | → `sections/subscriptions-and-notifications.md` |

### Migration & Support

| Section | Files | Description | Index |
|---------|-------|-------------|-------|
| **Migrations** | 48 | Importing repos, migrating to GitHub | → `sections/migrations.md` |
| **Support** | 15 | Getting help, contacting support | → `sections/support.md` |

### Other

| Section | Files | Description | Index |
|---------|-------|-------------|-------|
| **Search** | 1 | GitHub search | → `sections/search-github.md` |
| **Site Policy** | 72 | Terms, privacy, policies | → `sections/site-policy.md` |
| **Sponsors** | 34 | GitHub Sponsors | → `sections/sponsors.md` |
| **Nonprofit** | 12 | GitHub for nonprofits | → `sections/nonprofit.md` |
| **Video Transcripts** | 4 | Video content transcripts | → `sections/video-transcripts.md` |

---

## How to Use This Corpus

1. **Find your section** in the tables above
2. **Open the section index** (e.g., `sections/actions.md`)
3. **Find the specific doc** and note its path (e.g., `docs:actions/concepts/workflows.md`)
4. **Read the doc** from `.source/docs/content/{path}`

For the GraphQL schema, use Grep patterns shown above instead of reading the full file.
