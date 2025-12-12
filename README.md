# hiivmind-corpus-github

A Claude Code plugin marketplace providing comprehensive GitHub documentation corpus for AI-assisted development.

## What This Is

This is a **documentation corpus** - a pre-indexed collection of official GitHub documentation that enables Claude to accurately answer questions about GitHub features, APIs, and best practices. Instead of relying on training data or web searches, Claude can reference the actual documentation.

## Included Corpora

| Plugin                        | Files                       | Description                                                                      |
|:------------------------------|:----------------------------|:---------------------------------------------------------------------------------|
| `hiivmind-corpus-github-docs` | 3,346 docs + GraphQL schema | Official GitHub documentation from [github/docs](https://github.com/github/docs) |

### Complete Coverage

**Development & Automation** (1,037 docs)
| Section                        | Docs |                                      Description |
|:-------------------------------|-----:|-------------------------------------------------:|
| Actions                        |  239 |      Workflows, runners, reusable actions, CI/CD |
| Copilot                        |  321 |      GitHub Copilot setup, usage, customization  |
| REST API                       |  292 |       REST API endpoints, authentication, guides |
| Apps                           |  115 |    GitHub Apps, OAuth Apps, webhooks integration |
| GraphQL                        |   27 |              GraphQL API guides and reference    |
| Webhooks                       |   22 |                Webhook events, payloads, delivery |
| GitHub Models                  |   13 |                            AI models in GitHub   |
| GitHub CLI                     |    8 |                            gh command-line tool  |

**Security** (522 docs)
| Section                        | Docs |                                      Description |
|:-------------------------------|-----:|-------------------------------------------------:|
| Code Security                  |  443 |   Code scanning, CodeQL, secret scanning, GHAS   |
| Authentication                 |   79 |                        SSO, 2FA, PATs, SSH keys  |

**Repository Management** (369 docs)
| Section                        | Docs |                                      Description |
|:-------------------------------|-----:|-------------------------------------------------:|
| Repositories                   |  127 |        Repo settings, branches, releases, files  |
| Issues                         |  104 |           Issues, labels, milestones, projects   |
| Pull Requests                  |   68 |                 PRs, reviews, merging, conflicts |
| Pages                          |   29 |                            GitHub Pages hosting  |
| Packages                       |   24 |                       GitHub Packages registry   |
| Discussions                    |   17 |                          Community discussions   |

**Organization & Enterprise** (693 docs)
| Section                        | Docs |                                      Description |
|:-------------------------------|-----:|-------------------------------------------------:|
| Admin                          |  392 |              Enterprise administration, policies |
| Organizations                  |  166 |              Org management, teams, permissions  |
| Billing                        |   98 |                  Plans, usage, spending limits   |
| Enterprise Onboarding          |   37 |                        Enterprise setup guides   |

**Getting Started & Learning** (255 docs)
| Section                        | Docs |                                      Description |
|:-------------------------------|-----:|-------------------------------------------------:|
| Get Started                    |  117 |               Onboarding, quickstarts, tutorials |
| Education                      |   52 |                    GitHub Education, Classroom   |
| Contributing                   |   43 |                   Contributing to open source    |
| Communities                    |   43 |                          Building communities    |

**Tools & Environments** (164 docs)
| Section                        | Docs |                                      Description |
|:-------------------------------|-----:|-------------------------------------------------:|
| Codespaces                     |   97 |               Cloud development environments     |
| Desktop                        |   50 |                            GitHub Desktop app    |
| Integrations                   |   17 |                      Third-party integrations    |

**Account & Settings** (92 docs)
| Section                        | Docs |                                      Description |
|:-------------------------------|-----:|-------------------------------------------------:|
| Account and Profile            |   68 |          User settings, profiles, notifications  |
| Subscriptions and Notifications|   24 |                          Notification settings   |

**Migration & Support** (63 docs)
| Section                        | Docs |                                      Description |
|:-------------------------------|-----:|-------------------------------------------------:|
| Migrations                     |   48 |            Importing repos, migrating to GitHub  |
| Support                        |   15 |                Getting help, contacting support  |

**Other** (123 docs)
| Section                        | Docs |                                      Description |
|:-------------------------------|-----:|-------------------------------------------------:|
| Site Policy                    |   72 |                      Terms, privacy, policies    |
| Sponsors                       |   34 |                               GitHub Sponsors    |
| Nonprofit                      |   12 |                        GitHub for nonprofits     |
| Video Transcripts              |    4 |                      Video content transcripts   |
| Search                         |    1 |                                  GitHub search   |

**Plus:** Complete GraphQL schema (70k lines, 957 types, 381 inputs, 237 enums)

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

| Skill                       | Purpose                                |
|:----------------------------|:---------------------------------------|
| `hiivmind-corpus-refresh`   | Update index when upstream docs change |
| `hiivmind-corpus-enhance`   | Add depth to specific topics           |
| `hiivmind-corpus-add-source`| Add new documentation sources          |

To refresh the corpus when GitHub docs update:
```
"Refresh the GitHub docs corpus from upstream"
```

## Requirements

- Claude Code with plugin support
- `hiivmind-corpus` meta-plugin (for maintenance operations)

## License

MIT
