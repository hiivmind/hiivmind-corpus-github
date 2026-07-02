# Copilot

GitHub Copilot documentation - AI pair programming, chat, and code suggestions.

> **582 files** | Source: `docs:copilot/`

---

## Getting Started

- **Quickstart** `docs:copilot/get-started/quickstart.md` - Get started with Copilot
- **What is Copilot** `docs:copilot/get-started/what-is-copilot.md` - Overview
- **Best Practices** `docs:copilot/get-started/best-practices.md` - Tips for effective use
- **Supported Languages** `docs:copilot/get-started/supported-languages.md` - Language support

---

- **Adopting GitHub Copilot in your enterprise** `docs:copilot/get-started/enterprise-ai-governance.md` — Adopt the latest GitHub Copilot features without compromising on control and governance.
## Concepts

### Core Features

- **Chat** `docs:copilot/concepts/chat.md` - Copilot Chat overview
- **Completions** `docs:copilot/concepts/completions/index.md` - Code completions
- **Prompting** `docs:copilot/concepts/prompting/index.md` - Effective prompting
- **Context** `docs:copilot/concepts/context/index.md` - How Copilot uses context

### Agents & Tools

- **Agents** `docs:copilot/concepts/agents/index.md` - Copilot agents overview
- **Tools** `docs:copilot/concepts/tools/index.md` - Tool integrations
- **MCP Management** `docs:copilot/concepts/mcp-management.md` - Model Context Protocol

### Administration

- **Policies** `docs:copilot/concepts/policies.md` - Policy management
- **Billing** `docs:copilot/concepts/billing/index.md` - Billing concepts
- **Enterprise Accounts** `docs:copilot/concepts/about-enterprise-accounts-for-copilot-business.md`
- **Network Settings** `docs:copilot/concepts/network-settings.md` - Network configuration
- **Rate Limits** `docs:copilot/concepts/rate-limits.md` - Usage limits

### Experimental

- **Spark** `docs:copilot/concepts/spark.md` - Copilot Spark

---

- **About agent apps** `docs:copilot/concepts/agents/agent-apps.md` — Agent Apps Caps let you use partner-built agents directly in your workflows on Github, powered by your Copilot subscr...
- **About agent management** `docs:copilot/concepts/agents/cloud-agent/agent-management.md` — Use one centralized control page to jump between agent sessions, check progress, and stay in control without losing y...
- **About agent skills** `docs:copilot/concepts/agents/about-agent-skills.md` — Skills allow Copilot to perform specialized tasks.
- **About Copilot automations** `docs:copilot/concepts/agents/cloud-agent/about-automations.md` — Copilot Automations let you run Copilot cloud agent automatically, on a schedule or in response to events in a reposi...
- **About Copilot Copilot Auto Model Selection Short** `docs:copilot/concepts/models/auto-model-selection.md` — Automatically select the best model for each task.
- **About custom agents** `docs:copilot/concepts/agents/cloud-agent/about-custom-agents.md` — Custom Agents enhance Copilot with assistance tailored to your needs.
- **About custom agents** `docs:copilot/concepts/agents/copilot-cli/about-custom-agents.md` — Custom Agents enhance Copilot with assistance tailored to your needs.
- **About enterprise-managed plugin standards** `docs:copilot/concepts/agents/about-enterprise-plugin-standards.md` — Enterprise administrators can centrally define plugin policies for users, ensuring consistent plugin availability.
- **About GitHub Agentic Workflows** `docs:copilot/concepts/agents/about-github-agentic-workflows.md` — Automate repetitive repository work with natural language instructions executed by AI coding agents in GitHub Actions.
- **About GitHub Copilot CLI** `docs:copilot/concepts/agents/copilot-cli/about-copilot-cli.md` — Find out about using Copilot from the command line.
- **About GitHub Copilot CLI session data** `docs:copilot/concepts/agents/copilot-cli/chronicle.md` — Your Copilot CLI sessions build a searchable history of everything you have worked on. Query past sessions with natur...
- **About GitHub Copilot cloud agent** `docs:copilot/concepts/agents/cloud-agent/about-cloud-agent.md` — Copilot can research a repository, create an implementation plan, and make code changes on a branch. You can review t...
- **About GitHub Copilot Memory** `docs:copilot/concepts/agents/copilot-memory.md` — Copilot Memory helps Copilot become more effective over time by remembering facts about your repositories and your pe...
- **About GitHub Copilot plugins** `docs:copilot/concepts/agents/about-plugins.md` — Plugins are installable packages that extend Copilot with reusable agents, skills, hooks, and integrations.
- **About hooks for GitHub Copilot** `docs:copilot/concepts/agents/hooks.md` — Extend and customize GitHub Copilot agent behavior by executing custom shell commands at key points during agent exec...
- **About remote control of GitHub Copilot CLI sessions** `docs:copilot/concepts/agents/copilot-cli/about-remote-control.md` — Remote control lets you monitor and steer a Copilot CLI session from Dotcom The Website or Mobile, even after you''ve...
- **About Sandbox** `docs:copilot/concepts/about-cloud-and-local-sandboxes.md` — Sandbox Caps provide isolated execution environments that let Copilot safely interact with code, tools, filesystem, a...
- **About the GitHub Copilot app** `docs:copilot/concepts/agents/github-copilot-app.md` — The GitHub Copilot App is a desktop application for agent-driven development that brings parallel workstreams, Github...
- **About the rubber duck agent** `docs:copilot/concepts/agents/copilot-cli/rubber-duck.md` — The rubber duck agent is a built-in critic that gives Copilot a constructive second opinion on its own plans, code, a...
- **About third-party coding agents** `docs:copilot/concepts/agents/about-third-party-coding-agents.md` — You can use third-party coding agents alongside Copilot cloud agent to work asynchronously on your development tasks ...
- **Allowing GitHub Copilot CLI to work autonomously** `docs:copilot/concepts/agents/copilot-cli/autopilot.md` — The CLI''s autopilot mode lets Copilot CLI work autonomously on a task, carrying out multiple steps until the task is...
- **Anthropic Claude** `docs:copilot/concepts/agents/anthropic-claude.md` — Use the Anthropic Claude coding agent powered by Copilot.
- **Base and long-term support (LTS) models** `docs:copilot/concepts/models/fallback-and-lts-models.md` — Learn about base models, long-term support (LTS) models, and how they affect model availability for enterprises using...
- **Budgets for usage-based billing** `docs:copilot/concepts/billing/budgets-for-usage-based-billing.md` — Under usage-based billing, budget controls at the user, organization, cost center, and enterprise levels determine ho...
- **Canceling a GitHub Copilot CLI operation and rolling back changes** `docs:copilot/concepts/agents/copilot-cli/cancel-and-roll-back.md` — Find out about the different ways to cancel an active Copilot operation, and how to roll back changes made during a s...
- **Comparing GitHub Copilot CLI customization features** `docs:copilot/concepts/agents/copilot-cli/comparing-cli-features.md` — Find out about the various ways you can customize Copilot: what they do, and when to use them.
- **Concepts for GitHub Copilot CLI** `docs:copilot/concepts/agents/copilot-cli/index.md` — Learn how you can use GitHub Copilot in your terminal.
- **Concepts for GitHub Copilot cloud agent** `docs:copilot/concepts/agents/cloud-agent/index.md` — Learn how Copilot cloud agent can carry out research, planning and coding tasks for you, working independently in the...
- **FedRAMP-compliant models for GitHub Copilot** `docs:copilot/concepts/models/fedramp-models.md` — Restrict users to models with FedRAMP Moderate certification.
- **GitHub Copilot usage metrics** `docs:copilot/concepts/copilot-usage-metrics/copilot-metrics.md` — Copilot usage metrics provide visibility into how Copilot is adopted and used across your organization, including eng...
- **GitHub Copilot usage metrics** `docs:copilot/concepts/copilot-usage-metrics/index.md` — Track how your teams are using and adopting GitHub Copilot with detailed usage metrics.
- **Loading tools on demand with tool search** `docs:copilot/concepts/agents/copilot-cli/tool-search.md` — Tool search keeps your context small by letting Copilot CLI load external tools only when a task needs them.
- **Managing access to GitHub Copilot cloud agent** `docs:copilot/concepts/agents/cloud-agent/access-management.md` — Find out about Copilot cloud agent policies available for Copilot Enterprise and Copilot For Business, and about disa...
- **Managing context in GitHub Copilot CLI** `docs:copilot/concepts/agents/copilot-cli/context-management.md` — Understand how Copilot manages conversation context, what happens during long sessions, and how to stay in control of...
- **Models for GitHub Copilot** `docs:copilot/concepts/models/index.md` — Learn about the AI models available for GitHub Copilot.
- **Preparing for new features and models** `docs:copilot/concepts/preparing-for-new-features-and-models.md` — Stay informed about GitHub Copilot features and models, and make confident decisions about enabling them for your ent...
- **Researching with GitHub Copilot CLI** `docs:copilot/concepts/agents/copilot-cli/research.md` — The `/research` slash command turns Copilot into your research assistant, gathering in-depth information and insights...
- **Risks and mitigations for GitHub Copilot cloud agent** `docs:copilot/concepts/agents/cloud-agent/risks-and-mitigations.md` — How do Copilot cloud agent''s built-in security protections mitigate known risks?
- **Running tasks in parallel with the `/fleet` command** `docs:copilot/concepts/agents/copilot-cli/fleet.md` — The `/fleet` slash command lets Copilot CLI break down a complex request into smaller tasks and run them in parallel,...
- **Usage-based billing for individuals** `docs:copilot/concepts/billing/usage-based-billing-for-individuals.md` — Your Copilot plan includes a monthly allowance of AI credits. If you exhaust your AI credits, you can pay extra...
- **Usage-based billing for organizations and enterprises** `docs:copilot/concepts/billing/usage-based-billing-for-organizations-and-enterprises.md` — Under usage-based billing, Copilot usage in organizations and enterprises is measured in AI credits.
- **Using GitHub Copilot in JetBrains IDEs** `docs:copilot/concepts/agents/copilot-in-jetbrains.md` — Learn about the different ways to use GitHub Copilot in Jetbrains Ides, including the GitHub Copilot plugin, JetBrain...
- **Using LSP servers with GitHub Copilot CLI** `docs:copilot/concepts/agents/copilot-cli/lsp-servers.md` — LSP servers give Copilot CLI precise code intelligence, enabling it to navigate definitions, find references, and ren...
- **Utility models** `docs:copilot/concepts/models/utility-models.md` — Utility models power background Copilot features.
## How-Tos

### Setup

- **Set Up Copilot** `docs:copilot/how-tos/set-up/index.md` - Installation and setup
- **Configure Personal Settings** `docs:copilot/how-tos/configure-personal-settings/index.md`
- **Configure Custom Instructions** `docs:copilot/how-tos/configure-custom-instructions/index.md`
- **Configure Content Exclusion** `docs:copilot/how-tos/configure-content-exclusion/index.md`

### Using Copilot

- **Get Code Suggestions** `docs:copilot/how-tos/get-code-suggestions/index.md` - Completions
- **Chat with Copilot** `docs:copilot/how-tos/chat-with-copilot/index.md` - Using Chat
- **Provide Context** `docs:copilot/how-tos/provide-context/index.md` - Giving Copilot context
- **Use AI Models** `docs:copilot/how-tos/use-ai-models/index.md` - Model selection
- **Use Copilot Agents** `docs:copilot/how-tos/use-copilot-agents/index.md` - Agent mode
- **Common Tasks** `docs:copilot/how-tos/use-copilot-for-common-tasks/index.md` - Task examples

### Administration

- **Administer Copilot** `docs:copilot/how-tos/administer-copilot/index.md` - Organization management
- **Manage Account** `docs:copilot/how-tos/manage-your-account/index.md` - Account settings
- **Manage Spending** `docs:copilot/how-tos/manage-and-track-spending/index.md` - Cost management

### Troubleshooting

- **Troubleshoot Copilot** `docs:copilot/how-tos/troubleshoot-copilot/index.md` - Common issues

---

- **Access GitHub Copilot for free as a student** `docs:copilot/how-tos/copilot-on-github/set-up-copilot/enable-copilot/set-up-for-students.md` — Get free access to Copilot''s premium features as a verified student.
- **Add custom instructions for Copilot** `docs:copilot/how-tos/copilot-on-github/customize-copilot/add-custom-instructions/index.md` — Give GitHub Copilot persistent instructions to customize responses according to your needs.
- **Adding agent skills for GitHub Copilot** `docs:copilot/how-tos/copilot-on-github/customize-copilot/customize-cloud-agent/add-skills.md` — You can modify Copilot''s behavior and abilities when it works on particular tasks.
- **Adding agent skills for GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/add-skills.md` — Modify Copilot''s behavior and abilities when it works on particular tasks.
- **Adding custom instructions for GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/add-custom-instructions.md` — Give Copilot additional context on how to understand your project and how to build, test and validate its changes.
- **Adding GitHub Copilot cloud agent to your organization** `docs:copilot/how-tos/administer-copilot/manage-for-organization/add-copilot-cloud-agent.md` — Enable Copilot cloud agent for your members and control the repositories where it is available.
- **Adding LSP servers for GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/set-up-copilot-cli/add-lsp-servers.md` — You can add LSP servers to give Copilot CLI precise code intelligence, improving its ability to navigate definitions,...
- **Adding MCP servers for GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/add-mcp-servers.md` — Extend Copilot''s capabilities by connecting Model Context Protocol (MCP) servers to provide additional tools and con...
- **Adding personal custom instructions for GitHub Copilot** `docs:copilot/how-tos/copilot-on-github/customize-copilot/add-custom-instructions/add-personal-instructions.md` — Customize Copilot Chat responses to match your personal preferences.
- **Adding repository custom instructions for GitHub Copilot** `docs:copilot/how-tos/copilot-on-github/customize-copilot/add-custom-instructions/add-repository-instructions.md` — Create repository custom instructions files that give Copilot additional context on how to understand your project an...
- **Administering Copilot CLI for your enterprise** `docs:copilot/how-tos/copilot-cli/administer-copilot-cli-for-your-enterprise.md` — Control the use of Copilot CLI within your enterprise.
- **Allowing and denying tool use** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/allowing-tools.md` — Control which tools Copilot CLI can use to avoid unintended changes.
- **Asking GitHub Copilot questions in GitHub** `docs:copilot/how-tos/copilot-on-github/chat-with-copilot/chat-in-github.md` — Get instant answers about your code, repositories, and development questions — right from Github.
- **Asking GitHub Copilot questions in GitHub Mobile** `docs:copilot/how-tos/copilot-on-github/chat-with-copilot/chat-in-mobile.md` — Ask coding questions, explore repositories, and get help with pull requests in Mobile.
- **Authenticating GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/set-up-copilot-cli/authenticate-copilot-cli.md` — Authenticate Copilot CLI so that you can use Copilot directly from the command line.
- **Authentication** `docs:copilot/how-tos/copilot-sdk/auth/authenticate.md`
- **Authentication** `docs:copilot/how-tos/copilot-sdk/auth/index.md`
- **Automate with GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/automate-copilot-cli/index.md` — Learn how to use Copilot CLI in the terminal, in scripts, or in Actions workflows.
- **Automating tasks with Copilot CLI and GitHub Actions** `docs:copilot/how-tos/copilot-cli/automate-copilot-cli/automate-with-actions.md` — Integrate GitHub Copilot CLI into your GitHub Actions workflows.
- **Azure managed identity with BYOK** `docs:copilot/how-tos/copilot-sdk/setup/azure-managed-identity.md`
- **Backend services setup** `docs:copilot/how-tos/copilot-sdk/setup/backend-services.md`
- **Best practices for GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/cli-best-practices.md` — Learn how to get the most out of GitHub Copilot CLI.
- **Blocking agentic features in your enterprise** `docs:copilot/how-tos/administer-copilot/manage-for-enterprise/manage-agents/block-agentic-features.md` — Disable features for all users and repositories.
- **Browsing issues, pull requests, and gists from GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/browse-issues-prs-gists.md` — Use the tabs in an interactive Copilot CLI session to browse issues, pull requests and gists, without leaving the ter...
- **Build your first Copilot-powered app** `docs:copilot/how-tos/copilot-sdk/getting-started.md`
- **BYOK (bring your own key)** `docs:copilot/how-tos/copilot-sdk/auth/byok.md`
- **Changing the AI model for GitHub Copilot cloud agent** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/changing-the-ai-model.md` — In supported entrypoints, when starting a task with Copilot cloud agent, you can select the model used.
- **Chat with Copilot** `docs:copilot/how-tos/copilot-on-github/chat-with-copilot/index.md` — Learn how to use Copilot Chat Short on Github.
- **Cloud sessions** `docs:copilot/how-tos/copilot-sdk/features/cloud-sessions.md`
- **Configure secrets and variables for Copilot cloud agent** `docs:copilot/how-tos/copilot-on-github/customize-copilot/customize-cloud-agent/configure-secrets-and-variables.md` — Securely pass secrets and variables to Copilot cloud agent so it can access private resources and configure MCP servers.
- **Configure the development environment** `docs:copilot/how-tos/copilot-on-github/customize-copilot/customize-cloud-agent/customize-the-agent-environment.md` — Pre-install tools and dependencies so Copilot cloud agent can build, test, and validate changes reliably.
- **Configuring access to AI models in GitHub Copilot** `docs:copilot/how-tos/copilot-on-github/set-up-copilot/configure-access-to-ai-models.md` — Control which AI models your organization or enterprise can use with Copilot.
- **Configuring enterprise managed settings** `docs:copilot/how-tos/administer-copilot/manage-for-enterprise/manage-agents/configure-enterprise-managed-settings.md` — Configure enterprise managed settings by defining a `.github-managed-settings.yml` file in your enterprise's `.github...
- **Configuring GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/set-up-copilot-cli/configure-copilot-cli.md` — Configure trusted directories, tool access, and path and URL permissions for Copilot CLI
- **Configuring local sandbox settings** `docs:copilot/how-tos/cloud-and-local-sandboxes/configuring-local-sandbox-settings.md` — Use the `/sandbox` slash command in Copilot CLI to control how the local sandbox restricts filesystem access, network...
- **Configuring runners for GitHub Copilot cloud agent in your organization** `docs:copilot/how-tos/administer-copilot/manage-for-organization/configure-runner-for-coding-agent.md` — Configure the GitHub Actions runners used by Copilot cloud agent and control whether repositories can customize the r...
- **Configuring runners for GitHub Copilot code review** `docs:copilot/how-tos/copilot-on-github/set-up-copilot/configure-runners.md` — Use self-hosted runners or larger GitHub-hosted runners for Copilot Code-Review Short.
- **Configuring settings for GitHub Copilot cloud agent** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/configuring-agent-settings.md` — Learn how to configure settings for Copilot cloud agent
- **Configuring the GitHub MCP Server for GitHub Enterprise** `docs:copilot/how-tos/provide-context/use-mcp-in-your-ide/enterprise-configuration.md` — Learn how to configure the GitHub Model Context Protocol (MCP) server to work with GitHub Enterprise Server or Data R...
- **Configuring toolsets for the GitHub MCP Server** `docs:copilot/how-tos/provide-context/use-mcp-in-your-ide/configure-toolsets.md` — Learn how to configure toolsets and tools for the Github MCP server for fine-grained control and optimized performance.
- **Connecting GitHub Copilot CLI to VS Code** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/connecting-vs-code.md` — Connect Copilot CLI to VS Code to share context, trust settings, and output.
- **Copilot for Github tasks** `docs:copilot/how-tos/copilot-on-github/copilot-for-github-tasks/index.md` — Use Copilot to create issues, summarize pull requests, and perform other Github tasks directly from chat.
- **Copilot SDK** `docs:copilot/how-tos/copilot-sdk/index.md`
- **Copilot Spaces** `docs:copilot/how-tos/copilot-on-github/customize-copilot/copilot-spaces/index.md` — Organize and centralize relevant content into Copilot Spaces Short that ground Copilot''s responses in the right cont...
- **Creating a `.github-private` repository** `docs:copilot/how-tos/administer-copilot/manage-for-enterprise/manage-agents/create-github-private-repo.md` — A `.github-private` repository can serve as a designated source of governance settings for agents and plugins across ...
- **Creating a plugin for GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/plugins-creating.md` — Create a plugin to share customizations in an easy-to-install package.
- **Creating a plugin marketplace for GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/plugins-marketplace.md` — You can make CLI plugins that you''ve created easy to install by adding them to a marketplace.
- **Creating a pull request summary with GitHub Copilot** `docs:copilot/how-tos/copilot-on-github/copilot-for-github-tasks/create-a-pr-summary.md` — Generate an AI-powered summary of your pull request changes to help reviewers quickly understand what you changed and...
- **Creating and using custom agents for GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/create-custom-agents-for-cli.md` — Create specialized agents with tailored expertise for specific development tasks.
- **Creating automations with Copilot cloud agent** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/create-automations.md` — Create and manage Copilot automations to run Copilot cloud agent on a schedule or in response to events.
- **Creating custom agents for Copilot cloud agent** `docs:copilot/how-tos/copilot-on-github/customize-copilot/customize-cloud-agent/create-custom-agents.md` — You can create specialized agents with tailored expertise for specific development tasks.
- **Creating custom agents for Copilot cloud agent in your IDE** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/create-custom-agents-in-your-ide.md` — You can create specialized agents with tailored expertise for specific development tasks.
- **Creating GitHub Agentic Workflows** `docs:copilot/how-tos/github-agentic-workflows/creating-github-agentic-workflows.md` — Build custom AI-powered automations tailored to your repository''s needs.
- **Custom agents and sub-agent orchestration** `docs:copilot/how-tos/copilot-sdk/features/custom-agents.md`
- **Custom skills** `docs:copilot/how-tos/copilot-sdk/features/skills.md`
- **Customize agent workflows with hooks** `docs:copilot/how-tos/copilot-on-github/customize-copilot/customize-cloud-agent/use-hooks.md` — Run automated checks—like linting, formatting, or security scans—at key points during agent execution to enforce qual...
- **Customize Copilot** `docs:copilot/how-tos/copilot-on-github/customize-copilot/index.md` — Customize GitHub Copilot to fit your needs and get better results.
- **Customize Copilot cloud agent** `docs:copilot/how-tos/copilot-on-github/customize-copilot/customize-cloud-agent/index.md` — Create specialized agents with tailored expertise and extend their capabilities for Copilot cloud agent.
- **Customize Copilot for your project** `docs:copilot/how-tos/copilot-on-github/customize-copilot/customize-copilot-overview.md` — Set up custom instructions, create a specialized agent, and organize project context on Github.
- **Customize GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/index.md` — Learn how to customize Copilot CLI to maximize its usefulness when working on a specific project.
- **Customizing or disabling the firewall for GitHub Copilot cloud agent** `docs:copilot/how-tos/copilot-on-github/customize-copilot/customize-cloud-agent/customize-the-agent-firewall.md` — Learn how to control the domains and URLs that Copilot cloud agent can access.
- **Customizing the GitHub Copilot app** `docs:copilot/how-tos/github-copilot-app/customize-github-copilot-app.md` — Customize the GitHub Copilot App so it works the way you and your team do.
- **Debugging guide** `docs:copilot/how-tos/copilot-sdk/troubleshooting/debugging.md`
- **Default setup (bundled CLI)** `docs:copilot/how-tos/copilot-sdk/setup/bundled-cli.md`
- **Delegating tasks to Copilot** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/delegate-tasks-to-cca.md` — Use autopilot mode, or the `/delegate` slash command, to get Copilot to work autonomously on your behalf.
- **Enable Copilot** `docs:copilot/how-tos/copilot-on-github/set-up-copilot/enable-copilot/index.md` — Get started with GitHub Copilot for yourself, your organization, or your enterprise.
- **Enabling GitHub Copilot cloud agent in your enterprise** `docs:copilot/how-tos/administer-copilot/manage-for-enterprise/manage-agents/enable-copilot-cloud-agent.md` — Choose which organizations can use Copilot cloud agent and connect it to MCP servers.
- **Enabling GitHub Copilot code review in your enterprise** `docs:copilot/how-tos/administer-copilot/manage-for-enterprise/manage-agents/enable-copilot-code-review.md` — Apply consistent standards by having Copilot review every pull request.
- **Enabling or disabling cloud sandboxes for your organization** `docs:copilot/how-tos/cloud-and-local-sandboxes/enabling-or-disabling-cloud-sandboxes-for-your-organization.md` — You can control whether members of your organization can use cloud sandboxes by managing the sandbox access policy in...
- **Error handling hook** `docs:copilot/how-tos/copilot-sdk/hooks/error-handling.md`
- **Features** `docs:copilot/how-tos/copilot-sdk/features/index.md`
- **Finding and installing plugins for GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/plugins-finding-installing.md` — Extend Copilot''s functionality by installing plugins created by the community or by your team.
- **Fleet mode** `docs:copilot/how-tos/copilot-sdk/features/fleet-mode.md`
- **Get started with Copilot agents on Github** `docs:copilot/how-tos/copilot-on-github/use-copilot-agents/overview.md` — Try Copilot cloud agent end-to-end in about ten minutes.
- **Getting started with GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/cli-getting-started.md` — Quickly learn how to use GitHub Copilot CLI.
- **Getting started with prompts for Copilot Chat Short on Github** `docs:copilot/how-tos/copilot-on-github/chat-with-copilot/get-started-with-chat.md` — Explore example prompts to ask Copilot Chat Short about code, repositories, pull requests, and more.
- **Getting started with the GitHub Copilot app** `docs:copilot/how-tos/github-copilot-app/getting-started.md` — Sign in to the GitHub Copilot App, ask your first question in a quick chat, and then create a full agent session to m...
- **GitHub Agentic Workflows** `docs:copilot/how-tos/github-agentic-workflows/index.md` — Create AI-powered automations that run in your repositories on a schedule or in response to events.
- **GitHub Copilot App** `docs:copilot/how-tos/github-copilot-app/index.md` — A desktop application for agent-driven development that brings parallel workstreams, Github integration, and PR lifec...
- **GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/index.md` — Use Copilot directly from your terminal to answer questions, write and debug code, and interact with Github.
- **GitHub Copilot cloud agent** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/index.md` — Find out how Copilot can research a repository, plan and make code changes, and create pull requests for you to review.
- **GitHub Copilot on Github** `docs:copilot/how-tos/copilot-on-github/index.md` — Learn how to use GitHub Copilot on Github.
- **GitHub OAuth setup** `docs:copilot/how-tos/copilot-sdk/setup/github-oauth.md`
- **Image input** `docs:copilot/how-tos/copilot-sdk/features/image-input.md`
- **Installing GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/set-up-copilot-cli/install-copilot-cli.md` — Learn how to install Copilot CLI so that you can use Copilot directly from the command line.
- **Integrating Copilot cloud agent with Azure Boards** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/integrate-cloud-agent-with-azure-boards.md` — Use the Copilot integration in Azure Boards to send work items directly to Copilot cloud agent and generate pull requ...
- **Integrating Copilot cloud agent with Jira** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/integrate-cloud-agent-with-jira.md` — You can use the Github integration in Jira to provide context and open pull requests, all from within your Jira works...
- **Integrating Copilot cloud agent with Slack** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/integrate-cloud-agent-with-slack.md` — Provide context to the Copilot cloud agent and open pull requests, all from within your Slack workspace.
- **Integrations** `docs:copilot/how-tos/copilot-sdk/integrations/index.md` — Guides for using the GitHub Copilot SDK with other platforms and frameworks.
- **Invoking custom agents** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/invoke-custom-agents.md` — Use custom agents, skills, and MCP servers in Copilot CLI to extend its capabilities.
- **Kick off a task with Copilot agents on Github** `docs:copilot/how-tos/copilot-on-github/use-copilot-agents/kick-off-a-task.md` — Decide whether Copilot cloud agent creates a pull request immediately or works on a branch you review and iterate on ...
- **Local CLI setup** `docs:copilot/how-tos/copilot-sdk/setup/local-cli.md`
- **Managing agent sessions** `docs:copilot/how-tos/copilot-on-github/use-copilot-agents/manage-and-track-agents.md` — Monitor an agent''s progress in real time, steer it with follow-up prompts, and stop or archive sessions.
- **Managing availability of default models** `docs:copilot/how-tos/administer-copilot/manage-for-enterprise/manage-availability-of-default-models.md` — You can control which Copilot models are available to specific organizations.
- **Managing Copilot Memory** `docs:copilot/how-tos/use-copilot-agents/copilot-memory/index.md` — Manage and curate memories for Copilot agents.
- **Managing Copilot Memory for an organization or enterprise** `docs:copilot/how-tos/use-copilot-agents/copilot-memory/manage-as-administrator.md` — Manage Copilot Memory settings and stored memories for an organization or enterprise.
- **Managing Copilot Memory for your personal account** `docs:copilot/how-tos/use-copilot-agents/copilot-memory/manage-for-yourself.md` — Review and manage the coding conventions, preferences, and other details that Copilot has stored from your interactions.
- **Managing default models** `docs:copilot/how-tos/administer-copilot/manage-for-organization/manage-default-models.md` — Configure which default Copilot models are available to members of your organization.
- **Managing issues and pull requests with the GitHub Copilot app** `docs:copilot/how-tos/github-copilot-app/managing-issues-and-pull-requests.md` — Pick up an issue, direct an agent to implement changes, and land a pull request—all without leaving the GitHub Copilo...
- **Managing pull requests with the /pr command** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/manage-pull-requests.md` — Use the `/pr` slash command to view, create, and fix pull requests directly from Copilot CLI.
- **MCP server debugging guide** `docs:copilot/how-tos/copilot-sdk/troubleshooting/mcp-debugging.md`
- **Microsoft agent framework integration** `docs:copilot/how-tos/copilot-sdk/integrations/microsoft-agent-framework.md`
- **Monitoring your AI credits usage** `docs:copilot/how-tos/manage-and-track-spending/monitor-ai-usage.md` — Learn how to monitor the AI credits you consume when using Copilot.
- **Multi-tenancy and server deployments** `docs:copilot/how-tos/copilot-sdk/setup/multi-tenancy.md`
- **Observability** `docs:copilot/how-tos/copilot-sdk/observability/index.md` — Monitor and debug your GitHub Copilot SDK applications.
- **OpenTelemetry instrumentation for Copilot SDK** `docs:copilot/how-tos/copilot-sdk/observability/opentelemetry.md`
- **Overview of customizing GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/overview.md` — Copilot CLI works best when customized for your specific project and workflow.
- **Plugin directories** `docs:copilot/how-tos/copilot-sdk/features/plugin-directories.md`
- **Post-tool use hook** `docs:copilot/how-tos/copilot-sdk/hooks/post-tool-use.md`
- **Pre-tool use hook** `docs:copilot/how-tos/copilot-sdk/hooks/pre-tool-use.md` — The `onPreToolUse` hook is called **before** a tool executes. Use it to:
- **Quickstart for automating with GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/automate-copilot-cli/quickstart.md` — Build an automation with Copilot CLI in minutes.
- **Remote sessions** `docs:copilot/how-tos/copilot-sdk/features/remote-sessions.md`
- **Requesting a code review with GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/agentic-code-review.md` — Use Copilot CLI to review your code changes directly from the terminal.
- **Research, plan, and iterate on code changes with Copilot cloud agent** `docs:copilot/how-tos/copilot-on-github/use-copilot-agents/research-plan-iterate.md` — Perform deep research on a repository, create an implementation plan, and make iterative code changes on a branch, th...
- **Review output from Copilot** `docs:copilot/how-tos/copilot-on-github/use-copilot-agents/review-copilot-output.md` — Copilot pull requests deserve the same thorough review as any contribution.
- **Reviewing audit logs for GitHub Copilot** `docs:copilot/how-tos/administer-copilot/manage-for-enterprise/review-audit-logs.md` — Check for changes to settings or licenses in your Copilot plan.
- **Rolling back changes made during a GitHub Copilot CLI session** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/roll-back-changes.md` — Rewind your Copilot CLI session to a previous prompt to undo changes in conversation history, and optionally restore ...
- **Running GitHub Copilot CLI programmatically** `docs:copilot/how-tos/copilot-cli/automate-copilot-cli/run-cli-programmatically.md` — Use Copilot CLI in the terminal, in scripts, or in Actions workflows.
- **Sandbox Caps** `docs:copilot/how-tos/cloud-and-local-sandboxes/index.md` — Manage Sandbox for your organization.
- **Scaling and multi-tenancy** `docs:copilot/how-tos/copilot-sdk/setup/scaling.md`
- **Scheduling prompts in GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/automate-copilot-cli/schedule-prompts.md` — Use the `/every` and `/after` slash commands to submit a prompt to Copilot on a recurring schedule, or after a specif...
- **SDK and CLI compatibility** `docs:copilot/how-tos/copilot-sdk/troubleshooting/compatibility.md`
- **Session hooks** `docs:copilot/how-tos/copilot-sdk/hooks/hooks-overview.md`
- **Session lifecycle hooks** `docs:copilot/how-tos/copilot-sdk/hooks/session-lifecycle.md`
- **Session resume and persistence** `docs:copilot/how-tos/copilot-sdk/features/session-persistence.md`
- **Set up Copilot** `docs:copilot/how-tos/copilot-on-github/set-up-copilot/index.md` — Enable GitHub Copilot and configure features on Github.
- **Set up Copilot SDK** `docs:copilot/how-tos/copilot-sdk/setup/index.md` — Configure and deploy the GitHub Copilot SDK for your use case.
- **Setting an Ai Credit Singular session limit in GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/set-session-limit.md` — Limit the amount of AI credits Copilot can spend on a session to control costs and keep tasks predictable.
- **Setting up a dedicated enterprise for GitHub Copilot Business** `docs:copilot/how-tos/copilot-on-github/set-up-copilot/enable-copilot/set-up-a-dedicated-enterprise-for-copilot-business.md` — Create an enterprise account for managing Copilot Business Short licenses without adopting GitHub Enterprise.
- **Setting up GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/set-up-copilot-cli/index.md` — Learn how to install and configure GitHub Copilot in your terminal.
- **Setting up GitHub Copilot for your enterprise** `docs:copilot/how-tos/copilot-on-github/set-up-copilot/enable-copilot/set-up-for-enterprise.md` — Enable GitHub Copilot across your enterprise so developers can write code faster.
- **Setting up GitHub Copilot for your organization** `docs:copilot/how-tos/copilot-on-github/set-up-copilot/enable-copilot/set-up-for-organization.md` — Enable GitHub Copilot for your organization so members can write code faster.
- **Setting up GitHub Copilot for yourself** `docs:copilot/how-tos/copilot-on-github/set-up-copilot/enable-copilot/set-up-for-self.md` — Start using GitHub Copilot to write code faster on Github.
- **Setup guides** `docs:copilot/how-tos/copilot-sdk/setup/choosing-a-setup-path.md`
- **Speeding up task completion with the `/fleet` command** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/speed-up-task-completion.md` — Learn how you can speed up the completion of a multi-step implementation plan by using the `/fleet` slash command.
- **Starting GitHub Copilot sessions** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/start-copilot-sessions.md` — Choose your preferred way to start Copilot cloud agent sessions.
- **Steering a GitHub Copilot CLI session from another device** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/steer-remotely.md` — Enable remote control for a Copilot CLI session so you can monitor progress, respond to prompts, and continue working...
- **Steering agents in GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/steer-agents.md` — Guide Copilot during task execution to keep work on track with your intent.
- **Steering and queueing** `docs:copilot/how-tos/copilot-sdk/features/steering-and-queueing.md`
- **Streaming session events** `docs:copilot/how-tos/copilot-sdk/features/streaming-events.md`
- **The agent loop** `docs:copilot/how-tos/copilot-sdk/features/agent-loop.md`
- **Troubleshooting** `docs:copilot/how-tos/copilot-sdk/troubleshooting/index.md` — Diagnose and resolve issues with the GitHub Copilot SDK.
- **Troubleshooting GitHub Copilot CLI authentication** `docs:copilot/how-tos/copilot-cli/set-up-copilot-cli/troubleshoot-copilot-cli-auth.md` — Diagnose authentication failures when signing in to Copilot CLI.
- **Troubleshooting slow responses from GitHub Copilot** `docs:copilot/how-tos/troubleshoot-copilot/troubleshoot-copilot-slowness.md` — Troubleshooting help for slow responses from GitHub Copilot.
- **Use Copilot agents** `docs:copilot/how-tos/copilot-on-github/use-copilot-agents/index.md` — Delegate tasks to GitHub Copilot agents on Github, track their progress, and review the results.
- **Use GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/index.md` — Understand the different ways you can use GitHub Copilot in your terminal.
- **Use hooks** `docs:copilot/how-tos/copilot-sdk/hooks/index.md` — Detailed API reference for each session hook in the GitHub Copilot SDK.
- **Use voice input with Copilot CLI** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/voice-input.md` — Speak your prompts to GitHub Copilot CLI instead of typing them, using the CLI''s speech-to-text feature.
- **User prompt submitted hook** `docs:copilot/how-tos/copilot-sdk/hooks/user-prompt-submitted.md`
- **Using agent apps** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/use-agent-apps.md` — Start a partner-built agent from an issue, a pull request comment, or the Agents UI on Github.
- **Using automations in the GitHub Copilot app** `docs:copilot/how-tos/github-copilot-app/using-automations.md` — Automate recurring agent tasks so they run on a schedule or on demand, without manual intervention.
- **Using Copilot cloud agent from Raycast** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/use-cloud-agent-from-raycast.md` — Start and track Copilot cloud agent sessions from the Raycast launcher.
- **Using Copilot cloud agent from the GitHub CLI** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/use-cloud-agent-from-cli.md` — Start and track Copilot cloud agent sessions from the Cli.
- **Using Copilot cloud agent in your IDE** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/use-cloud-agent-in-your-ide.md` — Start and track Copilot cloud agent sessions from Visual Studio Code, JetBrains IDEs, Eclipse, and Vs.
- **Using Copilot cloud agent on GitHub** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/use-cloud-agent-on-github.md` — Start Copilot cloud agent sessions directly on Github, then iterate on the results without leaving your browser.
- **Using Copilot cloud agent on GitHub Mobile** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/use-cloud-agent-on-mobile.md` — Start and track Copilot cloud agent sessions from the Mobile app.
- **Using Copilot cloud agent via the API** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/use-cloud-agent-via-the-api.md` — You can start and manage Copilot cloud agent tasks programmatically using the REST API.
- **Using Copilot cloud agent via the GitHub MCP Server** `docs:copilot/how-tos/use-copilot-agents/cloud-agent/use-cloud-agent-with-mcp.md` — Start Copilot cloud agent sessions from any IDE or agentic tool that supports Model Context Protocol (MCP).
- **Using Copilot Code-Review on Github** `docs:copilot/how-tos/copilot-on-github/use-copilot-agents/copilot-code-review.md` — GitHub Copilot reviews your pull requests and suggests ready-to-apply changes, so you get fast, actionable feedback o...
- **Using deep links to open the GitHub Copilot app** `docs:copilot/how-tos/github-copilot-app/open-with-deep-links.md` — Use deep links to launch the GitHub Copilot App from the terminal, tickets, and internal tools, so people can jump di...
- **Using GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/overview.md` — Learn how to use GitHub Copilot from the command line.
- **Using GitHub Copilot CLI session data** `docs:copilot/how-tos/copilot-cli/use-copilot-cli/chronicle.md` — Resume previous Copilot CLI sessions, use the `/chronicle` slash command to get insights from your session history, a...
- **Using GitHub Copilot to create or update issues** `docs:copilot/how-tos/copilot-on-github/copilot-for-github-tasks/use-copilot-to-create-or-update-issues.md` — Use Copilot to quickly generate structured, high-quality issues from natural language or images, without filling out ...
- **Using hooks with GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/use-hooks.md` — Extend GitHub Copilot agent behavior with custom shell commands at key points during agent execution.
- **Using MCP servers with the GitHub Copilot SDK** `docs:copilot/how-tos/copilot-sdk/features/mcp.md`
- **Using Model Context Protocol in your IDE** `docs:copilot/how-tos/provide-context/use-mcp-in-your-ide/index.md` — Model Context Protocol (MCP) is a protocol that allows you to extend the capabilities of GitHub Copilot by integratin...
- **Using the GitHub MCP Server from Copilot Chat** `docs:copilot/how-tos/copilot-on-github/copilot-for-github-tasks/using-the-github-mcp-server-from-copilot-chat.md` — Perform Github tasks—like creating branches, merging pull requests, and searching for users—directly from Copilot Cha...
- **Using your own LLM models in GitHub Copilot CLI** `docs:copilot/how-tos/copilot-cli/customize-copilot/use-byok-models.md` — Use a model from an external provider of your choice in Copilot by supplying your own API key.
- **Using your own LLM models in the GitHub Copilot app** `docs:copilot/how-tos/github-copilot-app/use-byok-models.md` — Connect a model from an external provider of your choice by supplying your own API key, then use the model in agent s...
- **Viewing the code generation dashboard** `docs:copilot/how-tos/administer-copilot/view-code-generation.md` — The code generation dashboard shows how Copilot generates code across your enterprise, including activity from both u...
- **Working with agent sessions in the GitHub Copilot app** `docs:copilot/how-tos/github-copilot-app/agent-sessions.md` — Run multiple isolated agent sessions simultaneously, each with its own branch, and steer them using different session...
- **Working with canvas extensions in the GitHub Copilot app** `docs:copilot/how-tos/github-copilot-app/working-with-canvas-extensions.md` — Use canvases in the GitHub Copilot App to build shared, agent-driven artifacts and interfaces for human-agent collabo...
- **Working with hooks** `docs:copilot/how-tos/copilot-sdk/features/hooks.md`
- **Your first agentic workflow** `docs:copilot/how-tos/github-agentic-workflows/quickstart.md` — Get your first AI-powered automation running using a pre-built workflow and the GitHub CLI.
## Tutorials

### Getting Productive

- **Speed Up Development** `docs:copilot/tutorials/speed-up-development-work.md`
- **Explore a Codebase** `docs:copilot/tutorials/explore-a-codebase.md`
- **Write Tests** `docs:copilot/tutorials/write-tests.md`
- **Refactor Code** `docs:copilot/tutorials/refactor-code.md`
- **Learn a New Language** `docs:copilot/tutorials/learn-a-new-language.md`
- **Review AI-Generated Code** `docs:copilot/tutorials/review-ai-generated-code.md`
- **Vibe Coding** `docs:copilot/tutorials/vibe-coding.md`

### GitHub Integration

- **Explore Pull Requests** `docs:copilot/tutorials/explore-pull-requests.md`
- **Explore Issues and Discussions** `docs:copilot/tutorials/explore-issues-and-discussions.md`
- **Optimize Code Reviews** `docs:copilot/tutorials/optimize-code-reviews.md`

### Project Work

- **Plan a Project** `docs:copilot/tutorials/plan-a-project.md`
- **Migrate a Project** `docs:copilot/tutorials/migrate-a-project.md`
- **Upgrade Projects** `docs:copilot/tutorials/upgrade-projects.md`
- **Modernize Legacy Code** `docs:copilot/tutorials/modernize-legacy-code.md`
- **Reduce Technical Debt** `docs:copilot/tutorials/reduce-technical-debt.md`

### Customization

- **Use Custom Instructions** `docs:copilot/tutorials/use-custom-instructions.md`
- **Customization Library** `docs:copilot/tutorials/customization-library/index.md`
- **Compare AI Models** `docs:copilot/tutorials/compare-ai-models.md`

### Agents & MCP

- **Enhance Agent Mode with MCP** `docs:copilot/tutorials/enhance-agent-mode-with-mcp.md`

### Chat Cookbook

- **Copilot Chat Cookbook** `docs:copilot/tutorials/copilot-chat-cookbook/index.md` - Recipes and examples

### Enterprise Rollout

- **Roll Out at Scale** `docs:copilot/tutorials/roll-out-at-scale/index.md` - Enterprise deployment

### Spark

- **Spark Tutorials** `docs:copilot/tutorials/spark/index.md` - Copilot Spark

---

- **Building guardrails for GitHub Copilot cloud agent** `docs:copilot/tutorials/cloud-agent/build-guardrails.md` — Configure your enterprise so that Copilot cloud agent will operate in a secure, compliant environment.
- **Choosing your enterprise's plan for GitHub Copilot** `docs:copilot/tutorials/roll-out-at-scale/assign-licenses/choose-enterprise-plan.md` — Choose between Copilot Business Short and Copilot Enterprise Short.
- **Communicate effectively** `docs:copilot/tutorials/copilot-cookbook/communicate-effectively/index.md` — Discover ways that you can use GitHub Copilot to communicate effectively with your team and stakeholders.
- **Diagnosing CI test failures** `docs:copilot/tutorials/copilot-cookbook/debug-errors/diagnose-ci-test-failures.md` — Use Copilot CLI to pull CI logs, correlate failures to local code, and fix issues without leaving the terminal.
- **Filing issues without breaking your flow** `docs:copilot/tutorials/copilot-cookbook/document-code/filing-issues-without-breaking-your-flow.md` — When something catches your attention mid-task, use Copilot CLI to file a GitHub issue with code context, linked PRs,...
- **Generate code** `docs:copilot/tutorials/copilot-cookbook/generate-code/index.md` — Use GitHub Copilot to turn requirements into working code.
- **Getting started with budget controls** `docs:copilot/tutorials/budgets/getting-started-with-budget-controls.md` — Set up budget guardrails for your enterprise before your team starts consuming AI credits.
- **GitHub Copilot cloud agent** `docs:copilot/tutorials/cloud-agent/index.md` — Find out how to get great results from Copilot cloud agent.
- **Giving GitHub Copilot cloud agent access to resources in your organization** `docs:copilot/tutorials/cloud-agent/give-access-to-resources.md` — Get more out of Copilot by giving it access to approved MCP servers and internal packages.
- **Governing Copilot to support developer productivity** `docs:copilot/tutorials/roll-out-at-scale/govern-at-scale/govern-for-adoption.md` — Set a governance posture that balances compliance requirements with developer productivity, so your rollout succeeds ...
- **Governing GitHub Copilot at scale** `docs:copilot/tutorials/roll-out-at-scale/govern-at-scale/index.md` — Balance developer productivity with security, privacy, and compliance.
- **Implementing a feature from a GitHub Issue** `docs:copilot/tutorials/copilot-cookbook/generate-code/implement-a-feature.md` — Give a Github issue to GitHub Copilot CLI, then steer the conversation to implement the feature.
- **Maintaining codebase standards in a GitHub Copilot rollout** `docs:copilot/tutorials/roll-out-at-scale/govern-at-scale/maintain-codebase-standards.md` — Stay in control of your enterprise's code with rulesets, security features, and effective training.
- **Modernizing Java applications with GitHub Copilot** `docs:copilot/tutorials/modernize-java-applications.md` — GitHub Copilot can help modernize and migrate Java applications by assessing your codebase, identifying upgrade paths...
- **Optimizing your AI usage to maximize efficiency and reduce cost** `docs:copilot/tutorials/optimize-ai-usage.md` — Learn how to choose the right models, structure your prompts, and add guardrails so that Copilot completes tasks more...
- **Optimizing your budget configuration** `docs:copilot/tutorials/budgets/optimizing-your-budget-configuration.md` — Find the right combination of budget controls for your organization based on your size, structure, and spending goals.
- **Piloting GitHub Copilot cloud agent in your organization** `docs:copilot/tutorials/cloud-agent/pilot-cloud-agent.md` — Follow best practices to enable Copilot cloud agent in your organization.
- **Resources for getting approval of GitHub Copilot** `docs:copilot/tutorials/roll-out-at-scale/govern-at-scale/resources-for-approval.md` — Get ready to adopt Copilot by sending resources to legal and security teams in your company.
- **Setting up and optimizing budgets** `docs:copilot/tutorials/budgets/index.md` — Set up and optimize budget controls to manage your enterprise''s usage and spending on AI credits.
- **Triage and summarize repository activity** `docs:copilot/tutorials/copilot-cookbook/communicate-effectively/summarize-repository-activity.md` — Copilot can extract key information from repositories you follow to keep you up-to-date on recent activity.
- **Using Copilot CLI as your AI SME** `docs:copilot/tutorials/use-an-ai-sme.md` — Use Copilot CLI as an always-available subject matter expert to learn how a codebase works, so you can confidently ma...
- **Using GitHub Copilot cloud agent to improve a project** `docs:copilot/tutorials/cloud-agent/improve-a-project.md` — Find and fix problems in a project with Copilot cloud agent.
- **Using hooks with Copilot CLI for predictable, policy-compliant execution** `docs:copilot/tutorials/copilot-cli-hooks.md` — Use hooks to log user prompts and control which tools Copilot CLI can run in a repository, so teams can automate safe...
## Reference

### Keyboard & Cheat Sheet

- **Keyboard Shortcuts** `docs:copilot/reference/keyboard-shortcuts.md`
- **Cheat Sheet** `docs:copilot/reference/cheat-sheet.md`

### AI Models

- **AI Models Reference** `docs:copilot/reference/ai-models/index.md`

### Billing

- **Billing Reference** `docs:copilot/reference/copilot-billing/index.md`

### Metrics

- **Usage Metrics** `docs:copilot/reference/copilot-usage-metrics/index.md`
- **Metrics Data** `docs:copilot/reference/metrics-data.md`

### Configuration

- **Custom Agents Configuration** `docs:copilot/reference/custom-agents-configuration.md`
- **Copilot Allowlist** `docs:copilot/reference/copilot-allowlist-reference.md`
- **MCP Allowlist Enforcement** `docs:copilot/reference/mcp-allowlist-enforcement.md`
- **Review Excluded Files** `docs:copilot/reference/review-excluded-files.md`
- **Policy Conflicts** `docs:copilot/reference/policy-conflicts.md`

### Audit & Compliance

- **Agentic Audit Log Events** `docs:copilot/reference/agentic-audit-log-events.md`

---

- **Available filters for agent sessions** `docs:copilot/reference/agent-session-filters.md` — Search agentic activity in your enterprise with filters for agent sessions.
- **Copilot CLI ACP server** `docs:copilot/reference/copilot-cli-reference/acp-server.md` — Learn about GitHub Copilot CLI's Agent Client Protocol server.
- **Copilot CLI reference** `docs:copilot/reference/copilot-cli-reference/index.md` — Find information on options and settings for Copilot CLI.
- **Copilot customization cheat sheet** `docs:copilot/reference/customization-cheat-sheet.md` — Compare the different customization options for GitHub Copilot.
- **Copilot feature matrix** `docs:copilot/reference/copilot-feature-matrix.md` — Identify which IDEs support which GitHub Copilot features.
- **Example schema for Copilot usage metrics** `docs:copilot/reference/copilot-usage-metrics/example-schema.md` — See an example schema of the data returned by the Copilot usage metrics API.
- **GitHub Copilot CLI command reference** `docs:copilot/reference/copilot-cli-reference/cli-command-reference.md` — Find commands and keyboard shortcuts to help you use Copilot CLI effectively.
- **GitHub Copilot CLI configuration directory** `docs:copilot/reference/copilot-cli-reference/cli-config-dir-reference.md` — Find information about the `~/.copilot` directory, where Copilot CLI stores configuration, session data, and customiz...
- **GitHub Copilot CLI plugin reference** `docs:copilot/reference/copilot-cli-reference/cli-plugin-reference.md` — Find commands and configuration details for CLI plugins.
- **GitHub Copilot CLI programmatic reference** `docs:copilot/reference/copilot-cli-reference/cli-programmatic-reference.md` — Find options for running Copilot CLI programmatically.
- **GitHub Copilot hooks reference** `docs:copilot/reference/hooks-reference.md` — Find hook events, configuration formats, and input payloads for hooks in Copilot CLI and Copilot cloud agent.
- **GitHub Copilot request-based billing for annual plan subscribers (legacy)** `docs:copilot/reference/copilot-billing/request-based-billing-legacy/index.md` — Find information about GitHub Copilot''s legacy premium request-based billing model if you''re a Copilot Pro Short an...
- **Model multipliers for annual plans on request-based billing (legacy)** `docs:copilot/reference/copilot-billing/request-based-billing-legacy/model-multipliers-for-annual-plans.md` — Model multipliers for Copilot Pro Short and Copilot Pro Plus Short subscribers staying on annual plans under request-...
- **Models and pricing for GitHub Copilot** `docs:copilot/reference/copilot-billing/models-and-pricing.md` — See per-token pricing for the models available in GitHub Copilot and reference rates for additional usage across plans.
- **Requests in GitHub Copilot (legacy)** `docs:copilot/reference/copilot-billing/request-based-billing-legacy/copilot-requests.md` — Learn about requests in Copilot, including premium requests, how they work, and how to manage your usage effectively.
- **Support for different types of custom instructions** `docs:copilot/reference/custom-instructions-support.md` — Find out which environments support which types of custom instructions.
- **Supported surfaces for GitHub Copilot policies** `docs:copilot/reference/supported-surfaces-for-policies.md` — Which policies affect which Copilot features and surfaces?
- **Team-level Copilot usage metrics** `docs:copilot/reference/copilot-usage-metrics/team-level-metrics.md` — Construct team-level GitHub Copilot usage metrics by joining the daily user-teams report with the daily per-user usag...
- **What changed with Copilot billing (legacy)** `docs:copilot/reference/copilot-billing/request-based-billing-legacy/what-changed-with-billing.md` — Learn about what changed with billing and what your options are as a Copilot Pro Short and Copilot Pro Plus Short ann...
## Responsible Use

- **Responsible Use** `docs:copilot/responsible-use/index.md` - Guidelines for responsible AI use

- **Application card: GitHub Copilot Agents** `docs:copilot/responsible-use/agents.md` — Learn how to use GitHub Copilot agentic features responsibly by understanding their purposes, capabilities, and limit...
- **Application card: GitHub Copilot Chat** `docs:copilot/responsible-use/chat.md` — Learn how to use GitHub Copilot Chat responsibly by understanding its purposes, capabilities, and limitations.
- **Application card: GitHub Copilot inline suggestions** `docs:copilot/responsible-use/inline-suggestions.md` — Learn how to use GitHub Copilot inline suggestions responsibly by understanding their purposes, capabilities, and lim...