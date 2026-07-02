# REST API

GitHub REST API documentation - endpoints, authentication, and guides.

> **313 files** | Source: `docs:rest/`

---

## Getting Started

- **Quickstart** `docs:rest/quickstart.md` - Get started with the REST API
- **About the REST API** `docs:rest/about-the-rest-api/index.md` - Overview and concepts

### Using the REST API

- **Getting Started** `docs:rest/using-the-rest-api/getting-started-with-the-rest-api.md`
- **Rate Limits** `docs:rest/using-the-rest-api/rate-limits-for-the-rest-api.md`
- **Troubleshooting** `docs:rest/using-the-rest-api/troubleshooting-the-rest-api.md`

### Guides

- **Best Practices** `docs:rest/guides/best-practices-for-using-the-rest-api.md`
- **Scripting with REST API** `docs:rest/guides/scripting-with-the-rest-api.md`

---

## Authentication

- **Authentication Overview** `docs:rest/authentication/index.md`
- **Authenticating to REST API** `docs:rest/authentication/authenticating-to-the-rest-api.md`
- **Endpoints for Apps** `docs:rest/authentication/endpoints-available-for-github-app-installation-access-tokens.md`
- **Endpoints for Fine-Grained PATs** `docs:rest/authentication/endpoints-available-for-fine-grained-personal-access-tokens.md`

---

## API Endpoints by Resource

### Repositories

- **Repositories** `docs:rest/repos/index.md` - Repository management
- **Branches** `docs:rest/branches/index.md` - Branch operations
- **Commits** `docs:rest/commits/index.md` - Commit information
- **Releases** `docs:rest/releases/index.md` - Release management
- **Deploy Keys** `docs:rest/deploy-keys/index.md` - Repository deploy keys
- **Collaborators** `docs:rest/collaborators/index.md` - Repository collaborators

### Issues & Pull Requests

- **Issues** `docs:rest/issues/index.md` - Issue management
- **Pulls** `docs:rest/pulls/index.md` - Pull request operations
- **Reactions** `docs:rest/reactions/index.md` - Emoji reactions
- **Interactions** `docs:rest/interactions/index.md` - Interaction limits

### Projects

- **Projects** `docs:rest/projects/index.md` - Projects (v2)

### Actions

- **Actions** `docs:rest/actions/index.md` - GitHub Actions API
- **Checks** `docs:rest/checks/index.md` - Check runs and suites

### Code Security

- **Code Scanning** `docs:rest/code-scanning/index.md` - Code scanning alerts
- **Secret Scanning** `docs:rest/secret-scanning/index.md` - Secret scanning alerts
- **Security Advisories** `docs:rest/security-advisories/index.md` - Security advisories
- **Dependabot** `docs:rest/dependabot/index.md` - Dependabot alerts and updates
- **Dependency Graph** `docs:rest/dependency-graph/index.md` - Dependency information
- **Code Security** `docs:rest/code-security/index.md` - Security configurations

### Organizations

- **Organizations** `docs:rest/orgs/index.md` - Organization management
- **Teams** `docs:rest/teams/index.md` - Team management
- **Enterprise Teams** `docs:rest/enterprise-teams/index.md` - Enterprise team management

### Users

- **Users** `docs:rest/users/index.md` - User information
- **OAuth Authorizations** `docs:rest/oauth-authorizations/index.md` - OAuth tokens
- **Credentials** `docs:rest/credentials/index.md` - User credentials

### Apps

- **Apps** `docs:rest/apps/index.md` - GitHub Apps API

### Packages

- **Packages** `docs:rest/packages/index.md` - GitHub Packages API
- **Private Registries** `docs:rest/private-registries/index.md` - Private package registries

### Git Data

- **Git** `docs:rest/git/index.md` - Low-level Git operations
- **Gitignore** `docs:rest/gitignore/index.md` - Gitignore templates

### Activity

- **Activity** `docs:rest/activity/index.md` - Events, feeds, notifications

### Copilot

- **Copilot** `docs:rest/copilot/index.md` - Copilot API

### Pages & Gists

- **Pages** `docs:rest/pages/index.md` - GitHub Pages API
- **Gists** `docs:rest/gists/index.md` - Gist management

### Enterprise

- **Enterprise Admin** `docs:rest/enterprise-admin/index.md` - Enterprise administration
- **SCIM** `docs:rest/scim/index.md` - SCIM provisioning
- **Announcement Banners** `docs:rest/announcement-banners/index.md` - Enterprise announcements

### Codespaces

- **Codespaces** `docs:rest/codespaces/index.md` - Codespaces API

### Deployments

- **Deployments** `docs:rest/deployments/index.md` - Deployment management

### Billing

- **Billing** `docs:rest/billing/index.md` - Billing information

### Migrations

- **Migrations** `docs:rest/migrations/index.md` - Repository migrations

### Search

- **Search** `docs:rest/search/index.md` - GitHub search API

### GitHub Models

- **Models** `docs:rest/models/index.md` - AI models API

### Classroom

- **Classroom** `docs:rest/classroom/index.md` - GitHub Classroom API

### Miscellaneous

- **Emojis** `docs:rest/emojis/index.md` - GitHub emoji list
- **Licenses** `docs:rest/licenses/index.md` - License information
- **Markdown** `docs:rest/markdown/index.md` - Render markdown
- **Meta** `docs:rest/meta/index.md` - GitHub API metadata
- **Rate Limit** `docs:rest/rate-limit/index.md` - Rate limit status
- **Codes of Conduct** `docs:rest/codes-of-conduct/index.md` - Codes of conduct
- **Metrics** `docs:rest/metrics/index.md` - Repository metrics
- **Sponsors** `docs:rest/sponsors/index.md` - GitHub Sponsors API
- **Campaigns** `docs:rest/campaigns/index.md` - Campaigns API

---

- **REST API endpoints for Actions concurrency groups** `docs:rest/actions/concurrency-groups.md`

- **REST API endpoints for agent tasks** `docs:rest/agent-tasks/agent-tasks.md` — Use the REST API to start and manage Copilot cloud agent tasks

- **REST API endpoints for agent tasks** `docs:rest/agent-tasks/index.md`

- **REST API endpoints for agent secrets** `docs:rest/agents/secrets.md` — Use the REST API to manage secrets for agents.

- **REST API endpoints for variables** `docs:rest/agents/variables.md` — Use the REST API to manage variables.

- **REST endpoints for agents** `docs:rest/agents/index.md`

- **Usage reports** `docs:rest/billing/usage-reports.md` — Use the REST API to create and retrieve usage report exports for an enterprise.

- **REST API endpoints for code quality** `docs:rest/code-quality/code-quality.md` — Use the REST API to manage a code quality configuration.

- **REST API endpoints for code quality** `docs:rest/code-quality/index.md`

- **REST API endpoints for Copilot cloud agent management** `docs:rest/copilot/copilot-coding-agent-management.md`

- **REST API endpoints for Copilot cloud agent repository management** `docs:rest/copilot/copilot-cloud-agent-management.md` — Use the REST API to manage repository-level settings for Copilot cloud agent.

- **REST API endpoints for Copilot content exclusion management** `docs:rest/copilot/copilot-content-exclusion-management.md` — Use the REST API to manage Copilot content exclusion rules.

- **REST API endpoints for Copilot custom agents** `docs:rest/copilot/copilot-custom-agents.md` — Use the REST API to manage Copilot Custom Agents for your enterprise.

- **Copilot Spaces collaborators** `docs:rest/copilot-spaces/collaborators.md` — Use the REST API to manage collaborators for Copilot Spaces.

- **REST API endpoints for Copilot Spaces** `docs:rest/copilot-spaces/copilot-spaces.md` — Use the REST API to manage Copilot Spaces and related resources.

- **REST API endpoints for Copilot Spaces** `docs:rest/copilot-spaces/index.md`

- **REST API endpoints for Copilot Spaces resources** `docs:rest/copilot-spaces/resources.md` — Use the REST API to interact with Copilot Spaces resources.

- **REST API endpoints for enterprise credential authorizations** `docs:rest/enterprise-admin/credential-authorizations.md` — Use the REST API to manage enterprise credential authorizations.

- **REST API endpoints for issue field values** `docs:rest/issues/issue-field-values.md` — Use the REST API to view and manage issue field values for issues.

- **REST API endpoints for issue fields** `docs:rest/orgs/issue-fields.md` — Use the REST API to create and manage issue fields for an organization.

- **REST API endpoints for Project views** `docs:rest/projects/views.md` — Use the REST API to manage Project views

- **REST API endpoints for issue types** `docs:rest/repos/issue-types.md` — Use the REST API to manage issue types for a repository.
## Related

- **GraphQL API** → See `sections/graphql.md` for GraphQL documentation
- **GraphQL Schema** → See main index for `graphql-schema:schema.docs.graphql` (use Grep patterns)
