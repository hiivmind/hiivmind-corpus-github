# Code Security

GitHub Advanced Security (GHAS) documentation - code scanning, secret scanning, Dependabot, and supply chain security.

> **659 files** | Source: `docs:code-security/`

---

## Getting Started

- **Security Overview** `docs:code-security/getting-started/index.md` - Introduction to GitHub security features
- **Trialing GHAS** `docs:code-security/trialing-github-advanced-security/index.md` - Trial GitHub Advanced Security
- **Adopting GHAS at Scale** `docs:code-security/adopting-github-advanced-security-at-scale/index.md` - Enterprise rollout

---

## Code Scanning

Code analysis to find security vulnerabilities and coding errors.

### Overview

- **About Code Scanning** `docs:code-security/code-scanning/about/index.md`

### Configuration

- **Configure Code Scanning** `docs:code-security/code-scanning/configure/index.md`
- **Default Setup** `docs:code-security/code-scanning/configure/default-setup/index.md`
- **Advanced Setup** `docs:code-security/code-scanning/configure/advanced-setup/index.md`

### Managing Alerts

- **Manage Alerts** `docs:code-security/code-scanning/manage/index.md`
- **View Alerts** `docs:code-security/code-scanning/manage/view-alerts/index.md`
- **Dismiss Alerts** `docs:code-security/code-scanning/manage/dismiss-alerts/index.md`
- **Autofix** `docs:code-security/code-scanning/manage/autofix/index.md`

### Push Protection

- **Push Protection** `docs:code-security/code-scanning/push-protection/index.md`

### Integration

- **API** `docs:code-security/code-scanning/api/index.md`
- **Webhooks** `docs:code-security/code-scanning/webhooks/index.md`

### Troubleshooting

- **Troubleshooting** `docs:code-security/code-scanning/troubleshooting/index.md`

---

## CodeQL

GitHub's code analysis engine.

### CodeQL CLI

- **Getting Started** `docs:code-security/codeql-cli/getting-started/index.md`
- **Using CodeQL CLI** `docs:code-security/codeql-cli/using/index.md`
- **CodeQL Packs** `docs:code-security/codeql-cli/packs/index.md`
- **Reference** `docs:code-security/codeql-cli/reference/index.md`

### CodeQL for VS Code

- **Getting Started** `docs:code-security/codeql-for-vs-code/getting-started/index.md`
- **Using the Extension** `docs:code-security/codeql-for-vs-code/using/index.md`

---

## Secret Scanning

Detect secrets accidentally committed to repositories.

### Overview

- **About Secret Scanning** `docs:code-security/secret-scanning/about/index.md`

### Configuration

- **Enable Secret Scanning** `docs:code-security/secret-scanning/configure/index.md`
- **Push Protection** `docs:code-security/secret-scanning/push-protection/index.md`
- **Custom Patterns** `docs:code-security/secret-scanning/custom-patterns/index.md`

### Managing Alerts

- **Manage Alerts** `docs:code-security/secret-scanning/manage/index.md`
- **View Alerts** `docs:code-security/secret-scanning/manage/view-alerts/index.md`
- **Resolve Alerts** `docs:code-security/secret-scanning/manage/resolve-alerts/index.md`

### Validity Checks

- **Validity Checks** `docs:code-security/secret-scanning/validity-checks/index.md`

### Troubleshooting

- **Troubleshooting** `docs:code-security/secret-scanning/troubleshooting/index.md`

---

## Dependabot

Automated dependency updates and security alerts.

### Overview

- **About Dependabot** `docs:code-security/dependabot/about/index.md`

### Alerts

- **Dependabot Alerts** `docs:code-security/dependabot/alerts/index.md`
- **View Alerts** `docs:code-security/dependabot/alerts/view-alerts/index.md`
- **Configure Alerts** `docs:code-security/dependabot/alerts/configure-alerts/index.md`

### Security Updates

- **Security Updates** `docs:code-security/dependabot/security-updates/index.md`
- **Configure Updates** `docs:code-security/dependabot/security-updates/configure/index.md`

### Version Updates

- **Version Updates** `docs:code-security/dependabot/version-updates/index.md`
- **Configure Version Updates** `docs:code-security/dependabot/version-updates/configure/index.md`

### Configuration

- **Configuration File** `docs:code-security/dependabot/configuration/index.md`
- **dependabot.yml Reference** `docs:code-security/dependabot/configuration/reference/index.md`

### Grouped Updates

- **Grouped Updates** `docs:code-security/dependabot/grouped-updates/index.md`

### Troubleshooting

- **Troubleshooting** `docs:code-security/dependabot/troubleshooting/index.md`

---

## Supply Chain Security

Secure your software supply chain.

### Overview


### Dependency Graph

- **Dependency Graph** `docs:code-security/supply-chain-security/dependency-graph/index.md`
- **Understand the Graph** `docs:code-security/supply-chain-security/dependency-graph/about/index.md`
- **Configure** `docs:code-security/supply-chain-security/dependency-graph/configure/index.md`

### Dependency Review

- **Dependency Review** `docs:code-security/supply-chain-security/dependency-review/index.md`

### SBOM

- **SBOM Export** `docs:code-security/supply-chain-security/sbom/index.md`

---

## Security Advisories

Repository security advisories and the GitHub Advisory Database.

- **Repository Advisories** `docs:code-security/security-advisories/repository-security-advisories/index.md`
- **Global Advisories** `docs:code-security/security-advisories/global-security-advisories/index.md`

---

## Code Quality

Code quality tools and analysis.


---

## Securing Your Organization

Organization-wide security settings and policies.

- **Security Configurations** `docs:code-security/securing-your-organization/security-configurations/index.md`
- **Security Policies** `docs:code-security/securing-your-organization/security-policies/index.md`

---

## Security Overview

Dashboard and reporting for security across repositories.

- **View Security Data** `docs:code-security/security-overview/view/index.md`
- **Filter and Search** `docs:code-security/security-overview/filter/index.md`

## New in This Refresh

### Concepts

- **About Copilot Autofix for code scanning** `docs:code-security/concepts/code-scanning/copilot-autofix-for-code-scanning.md` — Copilot Autofix Short provides targeted recommendations to help you fix code scanning alerts and avoid introducing ne...
- **About linked artifacts** `docs:code-security/concepts/supply-chain-security/linked-artifacts.md` — The Virtual Registry helps you audit and prioritize your organization's builds on Github, regardless of where the art...
- **About open source license compliance** `docs:code-security/concepts/supply-chain-security/open-source-license-compliance.md` — Define and enforce license policy for dependencies in your repositories with open source license compliance.
- **About SARIF files for code scanning** `docs:code-security/concepts/code-scanning/sarif-files.md` — SARIF files convert third-party analyses into alerts on Github.
- **About secret scanning alerts** `docs:code-security/concepts/secret-security/about-alerts.md` — Learn about the different types of Alerts.
- **About setup types for code scanning** `docs:code-security/concepts/code-scanning/setup-types.md` — Depending on your needs, Github offers a default or advanced setup for code scanning.
- **About the dependabot.yml file** `docs:code-security/concepts/supply-chain-security/about-the-dependabot-yml-file.md` — The `dependabot.yml` controls automated dependency updates in your repository.
- **About the tool status page** `docs:code-security/concepts/code-scanning/tool-status-page.md` — The Tool Status Page provides visibility into the health and performance of code scanning tools in your repository.
- **Automatic Dependabot access to Github-hosted registries** `docs:code-security/concepts/supply-chain-security/automatic-dependabot-access-to-github-registries.md` — Keep your private dependencies up to date reliably by granting Dependabot automatic access to Registry and Container ...
- **Best practices for maintaining dependencies** `docs:code-security/concepts/supply-chain-security/best-practices-for-maintaining-dependencies.md` — Guidance and recommendations for maintaining the dependencies you use, including Github's security products that can ...
- **Best practices for selecting pilot repositories** `docs:code-security/concepts/security-at-scale/select-pilot-repositories.md` — The right pilot repositories demonstrate value quickly and prepare your organization for broader enablement of Gh Sec...
- **Bypass requests for push protection** `docs:code-security/concepts/secret-security/bypass-requests.md` — Learn how bypass requests work when push protection blocks commits containing secrets.
- **Code scanning alert tracking using issues** `docs:code-security/concepts/code-scanning/alert-tracking-with-issues.md` — Connect security findings to your team's workflow by linking code scanning alerts to issues for tracking and collabor...
- **Code scanning merge protection** `docs:code-security/concepts/code-scanning/merge-protection.md` — Code scanning rules prevent pull requests with potential vulnerabilities from being merged.
- **Code security risk assessment** `docs:code-security/concepts/code-scanning/risk-assessment.md` — Generate a free code security risk assessment to understand your organization's exposure to vulnerabilities.
- **CodeQL code scanning for compiled languages** `docs:code-security/concepts/code-scanning/codeql/codeql-for-compiled-languages.md` — Understand how CodeQL analyzes compiled languages, the build options available, and learn how you can customize the d...
- **CodeQL pull request alert metrics** `docs:code-security/concepts/code-scanning/pull-request-alert-metrics.md` — Understand CodeQL's performance in pull requests across your organizations.
- **CodeQL query packs** `docs:code-security/concepts/code-scanning/codeql/query-packs.md` — You can choose from different built-in CodeQL query suites to use in your CodeQL code scanning setup.
- **CodeQL query suites** `docs:code-security/concepts/code-scanning/codeql/codeql-query-suites.md` — You can choose from different built-in CodeQL query suites to use in your CodeQL code scanning setup.
- **Concepts for code scanning** `docs:code-security/concepts/code-scanning/index.md` — Learn core concepts for Github's code scanning features.
- **Concepts for CodeQL** `docs:code-security/concepts/code-scanning/codeql/index.md` — Understand the core concepts behind CodeQL and how it helps you find vulnerabilities and errors in your code.
- **Concepts for secret security** `docs:code-security/concepts/secret-security/index.md` — Learn core concepts for Github's secret security features.
- **Concepts for security and code quality** `docs:code-security/concepts/index.md` — Learn core concepts for Github's security and code quality features.
- **Concepts for security at scale** `docs:code-security/concepts/security-at-scale/index.md` — Learn about the concepts behind managing code security at scale in your organization or enterprise.
- **Concepts for vulnerability reporting and management** `docs:code-security/concepts/vulnerability-reporting-and-management/index.md` — Learn core concepts relating to vulnerability reporting and management on Github.
- **Custom CodeQL queries** `docs:code-security/concepts/code-scanning/codeql/custom-queries.md` — Custom queries extend CodeQL's built-in security analysis to detect vulnerabilities and enforce coding standards spec...
- **Custom patterns** `docs:code-security/concepts/secret-security/custom-patterns.md` — Detect secret types specific to your organization with custom patterns.
- **Delegated alert dismissal** `docs:code-security/concepts/security-at-scale/delegated-alert-dismissal.md` — Increase your governance over security alerts with delegated alert dismissal.
- **Delegated bypass for push protection** `docs:code-security/concepts/secret-security/delegated-bypass.md` — Maintain your secret security while unblocking trusted actors with delegated bypass for push protection.
- **Dependabot alerts** `docs:code-security/concepts/supply-chain-security/dependabot-alerts.md` — Dependabot Alerts help you find and fix vulnerable dependencies before they become security risks.
- **Dependabot auto-triage rules** `docs:code-security/concepts/supply-chain-security/dependabot-auto-triage-rules.md` — Control how Dependabot handles security alerts, including filtering, ignoring, snoozing, or triggering security updates.
- **Dependabot job logs** `docs:code-security/concepts/supply-chain-security/dependabot-job-logs.md` — Github logs every update job run by Dependabot, giving you visibility into version updates, security patches, and aut...
- **Dependabot malware alerts** `docs:code-security/concepts/supply-chain-security/malware-alerts.md` — Dependabot Malware Alerts help you identify malware in your dependencies to protect your project and its users.
- **Dependabot on GitHub Actions runners** `docs:code-security/concepts/supply-chain-security/dependabot-on-actions.md` — GitHub automatically runs the jobs that generate Dependabot pull requests on GitHub Actions if you have GitHub Action...
- **Dependabot pull requests** `docs:code-security/concepts/supply-chain-security/dependabot-pull-requests.md` — Understand the frequency and customization options of pull requests for version and security updates.
- **Dependabot version updates** `docs:code-security/concepts/supply-chain-security/dependabot-version-updates.md` — You can use Dependabot to keep the packages you use updated to the latest versions.
- **GitHub secret types** `docs:code-security/concepts/secret-security/secret-types.md` — Learn about the different types of secrets used by Github.
- **Global security advisories** `docs:code-security/concepts/vulnerability-reporting-and-management/global-security-advisories.md` — Global security advisories are CVEs and Company Short-originated advisories affecting the open source world, located ...
- **How the dependency graph recognizes dependencies** `docs:code-security/concepts/supply-chain-security/dependency-graph-data.md` — The dependency graph automatically analyzes manifest files. You can submit data for dependencies that cannot be detec...
- **Metrics for Dependabot alerts** `docs:code-security/concepts/supply-chain-security/dependabot-alert-metrics.md` — Use metrics to track and prioritize Dependabot Alerts across your organization.
- **Multi-ecosystem updates** `docs:code-security/concepts/supply-chain-security/multi-ecosystem-updates.md` — Multi-ecosystem updates combine dependency updates across multiple package ecosystems into a single pull request, red...
- **Multi-repository variant analysis** `docs:code-security/concepts/code-scanning/multi-repository-variant-analysis.md` — MRVA lets you test a query in Visual Studio Code by running it against a large number of repositories.
- **Public monitoring for secret scanning** `docs:code-security/concepts/secret-security/public-monitoring.md` — Public monitoring detects credentials leaked by your enterprise members in public repositories across Github, giving ...
- **Push protection** `docs:code-security/concepts/secret-security/push-protection.md` — Secure your secrets by stopping them from ever reaching your repository with push protection.
- **Push protection from the command line** `docs:code-security/concepts/secret-security/command-line-push-protection.md` — Understand how Github uses push protection to prevent secret leaks from the command line.
- **Repository properties for code scanning** `docs:code-security/concepts/code-scanning/repository-properties.md` — You can use repository properties to adjust code scanning to suit your needs.
- **Secret leakage risks** `docs:code-security/concepts/secret-security/secret-leakage-risks.md` — Secrets like API keys, passwords, and tokens committed to repositories can be exploited by unauthorized users, creati...
- **Secret scanning** `docs:code-security/concepts/secret-security/secret-scanning.md` — Prevent fraudulent use of your secrets by automatically detecting exposed credentials before they can be exploited.
- **Secret scanning push protection metrics** `docs:code-security/concepts/secret-security/push-protection-metrics.md` — Understand push protection''s performance across your organizations.
- **Secret security with GitHub** `docs:code-security/concepts/secret-security/secret-security-with-github.md` — Learn how Github's security tools can help you identify, remediate, and prevent secret leaks.
- **Security overview** `docs:code-security/concepts/security-at-scale/security-overview.md` — You can gain insights into the overall security landscape of your organization or enterprise and identify repositorie...
- **Supply chain security** `docs:code-security/concepts/supply-chain-security/index.md` — Github''s security features help you keep track of your projects'' dependencies and built artifacts.
- **Validity checks** `docs:code-security/concepts/secret-security/validity-checks.md` — Validity checks and extended metadata checks help you prioritize remediation of exposed credentials that pose immedia...

### How Tos

- **Accessing logs for CodeQL in Visual Studio Code** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-vs-code/accessing-logs.md` — If you need to troubleshoot problems with CodeQL for Visual Studio Code, there are several logs you can access.
- **Adding a security policy to your repository** `docs:code-security/how-tos/report-and-fix-vulnerabilities/configure-vulnerability-reporting/add-security-policy.md` — You can give instructions for how to report a security vulnerability in your project by adding a security policy to y...
- **Allowing use of Code Quality in your enterprise** `docs:code-security/how-tos/secure-at-scale/configure-enterprise-security/configure-specific-tools/allow-github-code-quality-in-enterprise.md` — Control Code Quality Short enablement for your repositories by defining policies.
- **Auditing your organization's builds on the Virtual Registry** `docs:code-security/how-tos/secure-your-supply-chain/establish-provenance-and-integrity/view-linked-artifacts.md` — View or export metadata for build runs, storage details, and deployment context.
- **Changing the "used by" data for a repository** `docs:code-security/how-tos/view-and-interpret-data/change-used-by-data.md` — Display your repository's dependents for a different package.
- **Checking out the CodeQL CLI source code** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-the-command-line/check-out-source-code.md` — Set up the Codeql Cli directly from the source code.
- **CodeQL code scanning for compiled languages** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/manage-your-configuration/codeql-for-compiled-languages.md` — Understand how CodeQL analyzes compiled languages, the build options available, and learn how you can customize the d...
- **Configure code scanning** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/configure-code-scanning/index.md` — Configure code scanning for your repositories by choosing between default or advanced setup and customizing advanced ...
- **Configure enterprise security** `docs:code-security/how-tos/secure-at-scale/configure-enterprise-security/index.md` — Configure and standardize security features across your enterprise, including establishing coverage, managing setting...
- **Configure specific tools** `docs:code-security/how-tos/secure-at-scale/configure-enterprise-security/configure-specific-tools/index.md` — Learn how to configure specific Github security and quality tools—such as the dependency graph, code scanning, secret...
- **Configure specific tools** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/configure-specific-tools/index.md` — Configure individual code security tools across your organization to assess risk, enable protections, and manage scan...
- **Configuring advanced setup for code scanning with CodeQL at scale** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/configure-specific-tools/configuring-advanced-setup-for-code-scanning-with-codeql-at-scale.md` — Establish a highly customizable code scanning setup at scale with a script.
- **Configuring automatic dependency submission for your repository** `docs:code-security/how-tos/secure-your-supply-chain/secure-your-dependencies/submit-dependencies-automatically.md` — You can use automatic dependency submission to submit transitive dependency data in your repository. This enables you...
- **Configuring default setup for code scanning at scale** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/configure-specific-tools/code-scanning-at-scale.md` — You can quickly configure code scanning for repositories across your organization using default setup.
- **Configuring Dependabot malware alerts** `docs:code-security/how-tos/secure-your-supply-chain/secure-your-dependencies/configure-malware-alerts.md` — Prevent malware attacks by identifying and remediating malicious dependencies.
- **Configuring Dependabot on GitHub-hosted runners** `docs:code-security/how-tos/secure-your-supply-chain/manage-your-dependency-security/configure-on-github-hosted-runners.md` — Enable Dependabot on Github-hosted runners to more easily identify Dependabot job errors and manually detect and trou...
- **Configuring Dependabot on self-hosted runners** `docs:code-security/how-tos/secure-your-supply-chain/manage-your-dependency-security/configure-on-self-hosted-runners.md` — You can configure self-hosted runners that Dependabot uses to access your private registries and internal network res...
- **Configuring multi-ecosystem updates for Dependabot** `docs:code-security/how-tos/secure-your-supply-chain/secure-your-dependencies/configuring-multi-ecosystem-updates.md` — Reduce the number of Dependabot pull requests you receive by grouping updates across multiple ecosystems into a singl...
- **Configuring notifications for Dependabot alerts** `docs:code-security/how-tos/secure-your-supply-chain/manage-your-dependency-security/configure-dependabot-notifications.md` — Optimize how you receive notifications about Dependabot Alerts.
- **Configuring open source license policies** `docs:code-security/how-tos/secure-your-supply-chain/manage-your-dependency-security/configure-license-policies.md` — Create and enforce open source license policies to control which licenses your dependencies are allowed to use.
- **Configuring security features in your organization** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/index.md` — Configure security across your organization by establishing coverage, managing settings, and controlling access to co...
- **Defining custom patterns for secret scanning** `docs:code-security/how-tos/secure-your-secrets/customize-leak-detection/define-custom-patterns.md` — Protect your unique secret types by defining custom patterns with regular expressions.
- **Disabling Code Quality** `docs:code-security/how-tos/maintain-quality-code/disable-code-quality.md` — Stop Code Quality Short scans and avoid charges before the feature becomes generally available.
- **Downloading CodeQL databases from GitHub** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-the-command-line/download-databases.md` — Expand the coverage of the Codeql Cli by adding ready-made databases.
- **Editing a custom security configuration** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/manage-your-coverage/edit-custom-configuration.md` — Meet the security needs of your repositories by editing your Custom Security Configuration.
- **Enabling delegated alert dismissal for Dependabot** `docs:code-security/how-tos/manage-security-alerts/manage-dependabot-alerts/enable-delegated-alert-dismissal.md` — Increase your governance over your Dependabot Alerts with delegated alert dismissal.
- **Enabling delegated bypass for push protection** `docs:code-security/how-tos/secure-your-secrets/manage-bypass-requests/enable-delegated-bypass.md` — Control who can push code containing secrets by requiring bypass approval from designated reviewers.
- **Enabling extended metadata checks for your repository** `docs:code-security/how-tos/secure-your-secrets/customize-leak-detection/enable-metadata-checks.md` — Learn how to enable extended metadata checks for detected secrets so alerts detected by secret scanning include addit...
- **Enabling public monitoring for your enterprise** `docs:code-security/how-tos/secure-at-scale/configure-enterprise-security/manage-your-coverage/enabling-public-monitoring-for-your-enterprise.md` — Start detecting secrets your enterprise members leak in public repositories outside your enterprise''s boundaries.
- **Enabling push protection for your repository** `docs:code-security/how-tos/secure-your-secrets/prevent-future-leaks/enable-push-protection.md` — With push protection, secret scanning blocks contributors from pushing secrets to a repository and generates an alert...
- **Enabling the dependency graph** `docs:code-security/how-tos/secure-your-supply-chain/secure-your-dependencies/enable-dependency-graph.md` — You can allow users to identify their projects' dependencies by enabling the dependency graph.
- **Enabling validity checks for your repository** `docs:code-security/how-tos/secure-your-secrets/customize-leak-detection/enable-validity-checks.md` — Enabling validity checks on your repository helps you prioritize the remediation of alerts as it tells you if a secre...
- **Establish complete coverage** `docs:code-security/how-tos/secure-at-scale/configure-enterprise-security/establish-complete-coverage/index.md` — Learn how to establish comprehensive, enterprise-wide security coverage by enabling Ghas, applying recommended or cus...
- **Establish complete coverage** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/establish-complete-coverage/index.md` — Ensure all repositories in your organization are covered by security protections by applying recommended or custom co...
- **Establishing provenance and integrity for your projects** `docs:code-security/how-tos/secure-your-supply-chain/establish-provenance-and-integrity/index.md` — Secure and audit your releases and artifacts.
- **Exempting trusted actors from push protection** `docs:code-security/how-tos/secure-your-secrets/manage-bypass-requests/grant-exemptions.md` — Reduce friction for trusted automation by granting exemptions from push protection.
- **Exploring data flow with path queries** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-vs-code/explore-data-flow.md` — Detect potential vulnerabilities by running path queries and analyzing your data flow.
- **Exploring GitHub Code Quality results in your organization** `docs:code-security/how-tos/view-and-interpret-data/analyze-organization-data/explore-code-quality.md` — Understand your organization's code health at a glance with the organization-level dashboard for Code Quality Short.
- **Exploring the structure of your source code** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-vs-code/explore-code-structure.md` — Visualize how your code maps to CodeQL classes in VS Code.
- **Filtering alerts in security overview** `docs:code-security/how-tos/manage-security-alerts/remediate-alerts-at-scale/filtering-alerts-in-security-overview.md` — Find the security alerts that matter most by filtering your security overview data.
- **Find and fix code vulnerabilities** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/index.md` — Identify vulnerabilities in your code by configuring and managing code scanning.
- **Finding repositories with security alerts using security overview** `docs:code-security/how-tos/view-and-interpret-data/analyze-organization-data/find-insecure-repositories.md` — Monitor and prioritize security alerts with security overview.
- **Giving security features access to private registries** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/manage-usage-and-access/giving-org-access-private-registries.md` — If your organization uses private registries, you can improve the results of code scanning analysis and enable Depend...
- **How-tos for analyzing security data for an organization** `docs:code-security/how-tos/view-and-interpret-data/analyze-organization-data/index.md` — Learn how to assess security risks, track feature adoption, view key metrics, and export data to analyze your organiz...
- **How-tos for bypass requests** `docs:code-security/how-tos/secure-your-secrets/manage-bypass-requests/index.md` — Control when contributors can push secrets by granting exemptions or bypass permissions to trusted actors.
- **How-tos for customizing secret leak detection** `docs:code-security/how-tos/secure-your-secrets/customize-leak-detection/index.md` — Learn how to customize Github's secret leak detection tools.
- **How-tos for detecting secret leaks** `docs:code-security/how-tos/secure-your-secrets/detect-secret-leaks/index.md` — Learn how to use Github's tools to detect secret leaks.
- **How-tos for fixing vulnerabilities** `docs:code-security/how-tos/report-and-fix-vulnerabilities/fix-reported-vulnerabilities/index.md` — Learn how to manage, create, edit, and publish security advisories for your repositories, collaborate on private repo...
- **How-tos for leak prevention** `docs:code-security/how-tos/secure-your-secrets/prevent-future-leaks/index.md` — Learn how to prevent future secret leaks with Github's push protection.
- **How-tos for reporting and fixing vulnerabilities** `docs:code-security/how-tos/report-and-fix-vulnerabilities/configure-vulnerability-reporting/index.md` — Learn how to establish security policies and enable private channels for reporting vulnerabilities in your repository.
- **How-tos for reporting and fixing vulnerabilities** `docs:code-security/how-tos/report-and-fix-vulnerabilities/index.md` — Learn how to report and fix vulnerabilities on Github.
- **How-tos for securing secrets** `docs:code-security/how-tos/secure-your-secrets/index.md` — Learn how to use Github's security and code quality features.
- **How-tos for security and code quality** `docs:code-security/how-tos/index.md` — Learn how to use Github's security and code quality features.
- **How-tos for viewing and interpreting security results** `docs:code-security/how-tos/view-and-interpret-data/index.md` — Discover how to analyze organization-level security data, interpret key insights and metrics, and export reports to a...
- **How-tos for working with leak prevention** `docs:code-security/how-tos/secure-your-secrets/work-with-leak-prevention/index.md` — Learn how to work with Github's push protection in different environments.
- **Index** `docs:code-security/how-tos/secure-your-supply-chain/index.md`
- **Integrate with existing tools** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/integrate-with-existing-tools/index.md` — Integrate code scanning with your existing tools and workflows by running scans in your CI system or uploading result...
- **Linking code scanning alerts to GitHub issues** `docs:code-security/how-tos/manage-security-alerts/manage-code-scanning-alerts/track-alerts-in-issues.md` — Create or connect Github issues to code scanning alerts to track security fixes in your team's workflow.
- **Maintain quality code** `docs:code-security/how-tos/maintain-quality-code/index.md` — Learn how to use Github's code security and code quality features to maintain high-quality code in your repositories.
- **Manage code scanning alerts** `docs:code-security/how-tos/manage-security-alerts/manage-code-scanning-alerts/index.md` — Discover how to assess, manage, and resolve code scanning alerts to keep your code secure.
- **Manage Dependabot alerts** `docs:code-security/how-tos/manage-security-alerts/manage-dependabot-alerts/index.md` — Learn how to view, manage, and resolve Dependabot Alerts to keep your dependencies secure.
- **Manage secret scanning alerts** `docs:code-security/how-tos/manage-security-alerts/manage-secret-scanning-alerts/index.md` — Discover how to monitor, manage, and resolve Alerts to keep your sensitive information secure.
- **Manage usage and access** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/manage-usage-and-access/index.md` — Control access to code security features and monitor usage across your organization, including access to private regi...
- **Manage your configuration** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/manage-your-configuration/index.md` — Manage and refine your code scanning configuration by monitoring tool status, updating default setup settings, and en...
- **Manage your coverage** `docs:code-security/how-tos/secure-at-scale/configure-enterprise-security/manage-your-coverage/index.md` — Review and manage your enterprise's repository security coverage by adjusting which repositories are included in your...
- **Manage your coverage** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/manage-your-coverage/index.md` — Review and adjust your organization's security coverage by managing which repositories are included in security confi...
- **Managing Dependabot malware alerts** `docs:code-security/how-tos/manage-security-alerts/manage-dependabot-alerts/manage-malware-alerts.md` — Find and triage malicious dependencies in your project with Dependabot Malware Alerts.
- **Managing pull requests for dependency updates** `docs:code-security/how-tos/secure-your-supply-chain/manage-your-dependency-security/manage-dependabot-prs.md` — You manage pull requests raised by Dependabot in much the same way as other pull requests, but there are some extra o...
- **Managing push protection for users** `docs:code-security/how-tos/secure-your-secrets/prevent-future-leaks/manage-user-push-protection.md` — You can control Github's ability to block your pushes that may contain secrets.
- **Managing requests to bypass push protection** `docs:code-security/how-tos/secure-your-secrets/manage-bypass-requests/manage-bypass-requests.md` — As a member of the bypass list for an organization or repository, you can review bypass requests from other members o...
- **Managing security alerts** `docs:code-security/how-tos/manage-security-alerts/index.md` — Manage alerts generated by security features.
- **Managing the CodeQL CLI in the VS Code extension** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-vs-code/manage-codeql-cli.md` — The CodeQL for Visual Studio Code extension uses the Codeql Cli to compile and run queries.
- **Managing your dependency security** `docs:code-security/how-tos/secure-your-supply-chain/manage-your-dependency-security/index.md` — Customize and configure features for dependency management.
- **Managing your paid use of As** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/manage-usage-and-access/managing-your-github-advanced-security-license-usage.md` — Control the costs of Gh Cs And Sp in your organization.
- **Pricing and enabling Gh Secret Protection** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/configure-specific-tools/protect-your-secrets.md` — Secure your organization's secrets within your budget by enabling Gh Secret Protection.
- **Privately reporting a security vulnerability** `docs:code-security/how-tos/report-and-fix-vulnerabilities/report-privately.md` — Some public repositories configure security advisories so that anyone can report security vulnerabilities directly an...
- **Publishing a repository security advisory** `docs:code-security/how-tos/report-and-fix-vulnerabilities/fix-reported-vulnerabilities/publish-repository-advisory.md` — You can publish a security advisory to alert your community about a security vulnerability in your project.
- **Publishing and using CodeQL packs** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-the-command-line/publish-and-use-packs.md` — Share or download a CodeQL pack, then analyze your CodeQL database.
- **Re-running Dependabot jobs on GitHub Actions** `docs:code-security/how-tos/secure-your-supply-chain/manage-your-dependency-security/re-run-dependabot-jobs.md` — Resolve run failures and manually update your dependencies by re-running Dependabot jobs.
- **Remediate alerts at scale** `docs:code-security/how-tos/manage-security-alerts/remediate-alerts-at-scale/index.md` — Learn how to remediate large volumes of alerts using clear processes and effective prioritization.
- **Removing artifacts from the Virtual Registry** `docs:code-security/how-tos/secure-your-supply-chain/establish-provenance-and-integrity/remove-linked-artifacts.md` — Set the storage and deployment status of artifacts to reflect that they are no longer in use.
- **Resolving alerts from secret scanning** `docs:code-security/how-tos/manage-security-alerts/manage-secret-scanning-alerts/resolving-alerts.md` — After reviewing the details of a secret scanning alert, you should fix and then close the alert.
- **Restricting code coverage on pull requests** `docs:code-security/how-tos/maintain-quality-code/restrict-code-coverage.md` — Protect your test coverage by automatically blocking pull requests that fall below the coverage levels your team requ...
- **Reviewing alert dismissal requests** `docs:code-security/how-tos/manage-security-alerts/remediate-alerts-at-scale/review-alert-dismissal-requests.md` — Triage and resolve security alerts in your organization or enterprise by regularly reviewing alert dismissal requests.
- **Running the code security risk assessment for your organization** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/configure-specific-tools/assess-your-vulnerability-risk.md` — Determine your organization's exposure to vulnerabilities by generating a Code Security Risk Assessment report.
- **Running the secret risk assessment for your organization** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/configure-specific-tools/assess-your-secret-risk.md` — Determine your organization's exposure to leaked secrets by generating a Secret Risk Assessment report.
- **Scan from the command line** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-the-command-line/index.md` — Run code scanning from the command line using the Codeql Cli to configure scans, customize queries, and troubleshoot ...
- **Scan from VS Code** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-vs-code/index.md` — Scan and analyze code from Visual Studio Code using CodeQL to write, test, and run queries, explore code structure, a...
- **Scanning for secrets with the GitHub MCP server** `docs:code-security/how-tos/use-ghas-with-ai-coding-agents/scan-for-secrets-with-github-mcp-server.md` — Detect exposed secrets in real time from your AI coding agent, before they ever reach your repository.
- **Secure at scale** `docs:code-security/how-tos/secure-at-scale/index.md` — Secure your codebase at scale by configuring security at the enterprise and organization levels and troubleshooting s...
- **Securing your dependencies** `docs:code-security/how-tos/secure-your-supply-chain/secure-your-dependencies/index.md` — Keep your supply chain secure by understanding and updating dependencies.
- **Set code scanning merge protection** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/manage-your-configuration/set-merge-protection.md` — Secure your codebase by blocking pull requests that fail code scanning checks.
- **Setting up code coverage for your repository** `docs:code-security/how-tos/maintain-quality-code/set-up-code-coverage.md` — Upload test coverage reports to see coverage results directly on pull requests, helping reviewers identify untested c...
- **Specifying command options in a CodeQL configuration file** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-the-command-line/specify-command-options.md` — Save time by adding your frequently used command options and custom CodeQL packs to a CodeQL configuration file.
- **Testing query help files** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-the-command-line/test-query-help-files.md` — Ensure your CodeQL query help files are valid by previewing them as Markdown.
- **Uploading storage and deployment data to the Virtual Registry** `docs:code-security/how-tos/secure-your-supply-chain/establish-provenance-and-integrity/upload-linked-artifacts.md` — Associate packages and builds in your organization with storage and deployment data.
- **Use GitHub Advanced Security with AI coding agents** `docs:code-security/how-tos/use-ghas-with-ai-coding-agents/index.md` — Catch secrets, vulnerabilities, and insecure dependencies while you code, directly from GitHub Copilot agent mode and...
- **Use the tool status page for code scanning** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/manage-your-configuration/use-the-tools-status-page-for-code-scanning.md` — View real-time tool status, identify configuration problems, and download reports to keep your code scanning analysis...
- **Using GitHub preset rules to prioritize Dependabot alerts** `docs:code-security/how-tos/secure-your-supply-chain/manage-your-dependency-security/prioritize-with-preset-rules.md` — Focus on alerts that matter by auto-dismissing low impact development alerts for npm dependencies.
- **Using incremental analysis with the CodeQL CLI** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-the-command-line/incremental-analysis.md` — Get faster CodeQL results on pull requests by analyzing only what changed. Incremental analysis can reduce scan times...
- **Viewing and filtering alerts from secret scanning** `docs:code-security/how-tos/manage-security-alerts/manage-secret-scanning-alerts/viewing-alerts.md` — Learn how to find and filter User AlertsUser Alerts alerts for your repository.
- **Viewing and updating Dependabot alerts** `docs:code-security/how-tos/manage-security-alerts/manage-dependabot-alerts/view-dependabot-alerts.md` — If Github discovers insecure dependencies in your project, you can view alert details on the Dependabot tab of your r...
- **Viewing code scanning logs from GitHub Actions** `docs:code-security/how-tos/view-and-interpret-data/view-code-scanning-logs.md` — View the output from a code scanning analysis in GitHub Actions.
- **Viewing Dependabot job logs** `docs:code-security/how-tos/view-and-interpret-data/view-dependabot-logs.md` — Access job logs to troubleshoot failed Dependabot Updates and understand what is happening.
- **Viewing metrics for custom patterns** `docs:code-security/how-tos/view-and-interpret-data/view-custom-pattern-metrics.md` — Find out how many alerts are being raised and addressed for a custom pattern.
- **Viewing metrics for Dependabot alerts** `docs:code-security/how-tos/view-and-interpret-data/analyze-organization-data/viewing-metrics-for-dependabot-alerts.md` — You can use security overview to see how many Dependabot Alerts are in repositories across your organization, to prio...
- **Viewing metrics for pull request alerts** `docs:code-security/how-tos/view-and-interpret-data/analyze-organization-data/viewing-metrics-for-pull-request-alerts.md` — Monitor CodeQL's performance in pull requests across your organizations to identify repositories where you may need t...
- **Viewing metrics for secret scanning push protection** `docs:code-security/how-tos/view-and-interpret-data/analyze-organization-data/viewing-metrics-for-secret-scanning-push-protection.md` — Monitor push protection's performance across your organization or enterprise to identify repositories where you may n...
- **Viewing public monitoring alerts** `docs:code-security/how-tos/view-and-interpret-data/analyze-organization-data/viewing-public-monitoring-alerts.md` — Find out which credentials your enterprise members have exposed in public repositories across Github.
- **Viewing security insights** `docs:code-security/how-tos/view-and-interpret-data/analyze-organization-data/viewing-security-insights.md` — Monitor your organization or enterprise security posture, identify high-risk repositories, and track alert remediatio...
- **Viewing your security risk assessment reports** `docs:code-security/how-tos/secure-at-scale/configure-organization-security/configure-specific-tools/viewing-your-security-risk-assessment-reports.md` — Understand your organization's exposure to leaked secrets and code vulnerabilities by viewing your most recent securi...
- **Writing custom queries for the CodeQL CLI** `docs:code-security/how-tos/find-and-fix-code-vulnerabilities/scan-from-the-command-line/write-custom-queries.md` — You can write your own CodeQL queries to find specific vulnerabilities and errors.

### Reference

- **About built-in CodeQL queries** `docs:code-security/reference/code-scanning/codeql/codeql-queries/built-in-queries.md` — Learn about the CodeQL queries that code scanning uses to analyze code.
- **Alerts found in generated code** `docs:code-security/reference/code-scanning/troubleshoot-analysis-errors/alerts-in-generated-code.md` — When analyzing your code with code scanning, you may wish to build only the code which you wish to analyze.
- **Automatic dependency submission** `docs:code-security/reference/supply-chain-security/automatic-dependency-submission.md` — Network access requirements, troubleshooting, and ecosystem-specific behavior for automatic dependency submission.
- **Code scanning logs** `docs:code-security/reference/code-scanning/code-scanning-logs.md` — You can view the output generated during code scanning analysis in Github.
- **CodeQL for Visual Studio Code reference** `docs:code-security/reference/code-scanning/codeql/codeql-for-vs-code/index.md` — Find troubleshooting and telemetry information for the CodeQL extension for VS Code.
- **Common security incident investigation areas** `docs:code-security/reference/security-incident-response/investigation-areas.md` — Reference for investigating security incidents across multiple attack vectors, including the key surfaces and tools t...
- **Custom patterns reference** `docs:code-security/reference/secret-security/custom-patterns.md` — Use specific regular expression syntax to define accurate custom patterns for secret scanning.
- **CWEs used by GitHub's preset Dependabot rules** `docs:code-security/reference/supply-chain-security/criteria-for-preset-rules.md` — Github uses industry-standard criteria to help you filter Dependabot Alerts.
- **Dependabot alert filters** `docs:code-security/reference/supply-chain-security/dependabot-alerts-filters.md` — Dependabot Alerts filters help you prioritize and manage alerts for vulnerable dependencies in your repositories.
- **Dependabot errors** `docs:code-security/reference/supply-chain-security/troubleshoot-dependabot/dependabot-errors.md` — Dependabot automatically maintains your dependencies, keeping your code secure and current. This reference helps you ...
- **Dependabot on GitHub Actions** `docs:code-security/reference/supply-chain-security/dependabot-on-actions.md` — Detailed information on using Dependabot with GitHub Actions.
- **Dependabot security updates reference** `docs:code-security/reference/supply-chain-security/dependabot-security-updates.md` — Find usage information for Dependabot Security Updates.
- **Dependency graph supported package ecosystems** `docs:code-security/reference/supply-chain-security/dependency-graph-supported-package-ecosystems.md` — Dependency graph supports a variety of ecosystems.
- **Diagnosing security configuration issues** `docs:code-security/reference/security-at-scale/troubleshoot-security-configurations/configuration-issue-diagnosis.md` — Identify repositories where the security configuration could not be attached, or where the configuration relationship...
- **GitHub Actions queries for CodeQL analysis** `docs:code-security/reference/code-scanning/codeql/codeql-queries/actions-built-in-queries.md` — Explore the queries that CodeQL uses to analyze code written in GitHub Actions workflow files when you select the `de...
- **Investigation tools for security incidents** `docs:code-security/reference/security-incident-response/investigation-tools.md` — The core Github tools you can use to investigate security incidents, what each tool is best used for, and common cons...
- **Java package metadata for Dependabot updates** `docs:code-security/reference/supply-chain-security/java-package-metadata-dependabot.md` — Include metadata in your `pom.xml` file to provide helpful links and context in Dependabot pull requests for Java pac...
- **Logs are not detailed enough** `docs:code-security/reference/code-scanning/troubleshoot-analysis-errors/logs-not-detailed-enough.md` — Increase log verbosity and generate debugging artifacts when logs lack diagnostic detail.
- **Permissions for security features** `docs:code-security/reference/permissions/index.md` — Find information about permissions related to Github's security features.
- **Queries for CodeQL analysis** `docs:code-security/reference/code-scanning/codeql/codeql-queries/index.md` — Explore the CodeQL queries that code scanning uses to analyze code.
- **Reference for code quality** `docs:code-security/reference/code-quality/index.md` — Find reference documentation for Code Quality Short.
- **Reference for code scanning** `docs:code-security/reference/code-scanning/index.md` — Find information to apply to your work with code scanning.
- **Reference for code scanning with CodeQL** `docs:code-security/reference/code-scanning/codeql/index.md` — Find information to apply to your work with CodeQL code scanning.
- **Reference for CodeQL queries** `docs:code-security/reference/code-quality/codeql-queries/index.md` — Find lists of CodeQL queries used by Code Quality Short for each supported programming language.
- **Reference for SARIF files for code scanning** `docs:code-security/reference/code-scanning/sarif-files/index.md` — Learn about and troubleshoot SARIF support for code scanning.
- **Reference for security and code quality** `docs:code-security/reference/index.md` — Find information to apply to your work with Github's security and code quality features.
- **Reference for security at scale** `docs:code-security/reference/security-at-scale/index.md` — Find information on filtering security overview and troubleshooting your security configurations.
- **Reference for security incident response** `docs:code-security/reference/security-incident-response/index.md` — Find reference information to support your investigation and response to security incidents.
- **Reference for supply chain security** `docs:code-security/reference/supply-chain-security/index.md` — Find information to apply to your work with Dependabot and the dependency graph.
- **Secret scanning pattern configuration data** `docs:code-security/reference/secret-security/secret-pattern-data.md` — Understand the data displayed in the secret scanning pattern configuration page to make informed decisions about push...
- **Secret security** `docs:code-security/reference/secret-security/index.md` — Learn about secret scanning patterns, risk report CSV contents, and Github secrets.
- **Security configuration enforcement** `docs:code-security/reference/security-at-scale/configuration-enforcement.md` — Understand the complexities of enforcing Security Configurations.
- **Security configuration statuses** `docs:code-security/reference/security-at-scale/configuration-statuses.md` — Each repository that has a Security Configuration applied to it has a configuration status that reflects the current ...
- **Security overview dashboard metrics** `docs:code-security/reference/security-at-scale/overview-dashboard-metrics.md` — Detailed explanations of metrics, calculations, and data visualizations on the overview page of your security overview.
- **Security overview permissions** `docs:code-security/reference/permissions/security-overview.md` — The actions you can take in security overview depend on your permissions for the repositories in your organization or...
- **Supported ecosystems and manifests for dependency scope** `docs:code-security/reference/supply-chain-security/supported-ecosystems-and-manifests-for-dependency-scope.md` — Dependabot Alerts supports a variety of ecosystems and manifests for dependency scope.
- **Supported secret scanning patterns** `docs:code-security/reference/secret-security/supported-secret-scanning-patterns.md` — Lists of supported secrets and the partners that Company Short works with to prevent fraudulent use of secrets that w...
- **Troubleshoot Dependabot** `docs:code-security/reference/supply-chain-security/troubleshoot-dependabot/index.md` — Resolve dependency security issues with error codes, diagnostic information, and solutions for common problems.
- **Troubleshoot security configurations** `docs:code-security/reference/security-at-scale/troubleshoot-security-configurations/index.md` — Identify and resolve issues with your security configurations by diagnosing common problems related to setup, coverag...
- **Troubleshooting SARIF uploads** `docs:code-security/reference/code-scanning/sarif-files/troubleshoot-sarif-uploads/index.md` — Identify and resolve issues when uploading SARIF files, including authentication problems, file validation errors, an...
- **Using the advanced functionality of the CodeQL CLI** `docs:code-security/reference/code-scanning/codeql/codeql-cli/index.md` — You can use the Codeql Cli to locally develop, test and run CodeQL queries on software projects.

### Responsible Use

- **Application card: GitHub security and quality AI features** `docs:code-security/responsible-use/security-and-quality-ai-features.md` — Use GitHub's AI-powered code security and code quality features responsibly by understanding their purposes, capabili...
- **Responsible use of Github's security and code quality features** `docs:code-security/responsible-use/index.md` — Use Github's security and code quality features responsibly by understanding their purposes, capabilities, and limita...

### Tutorials

- **Assessing the impact of GitHub Secret Protection** `docs:code-security/tutorials/remediate-leaked-secrets/assessing-ghsp-impact.md` — Measure how Gh Secret Protection Always reduces secret exposure across your organization, so you can demonstrate valu...
- **Customize code scanning** `docs:code-security/tutorials/customize-code-scanning/index.md` — Learn how to customize code scanning to meet your project's unique security needs by creating and using CodeQL packs ...
- **Fixing reported vulnerabilities** `docs:code-security/tutorials/fix-reported-vulnerabilities/index.md` — Build skills in collaborating on fixing security vulnerabilities in repositories.
- **Implement supply chain best practices** `docs:code-security/tutorials/implement-supply-chain-best-practices/index.md` — How to think about securing your user accounts, your code, and your build process
- **Improving the quality of your code** `docs:code-security/tutorials/improve-code-quality/index.md` — Build skills and knowledge about Code Quality through examples.
- **Interpreting code security risk assessment results** `docs:code-security/tutorials/secure-your-organization/interpret-code-security-risk-assessment.md` — Understand the results from your Code Security Risk Assessment and prioritize vulnerability remediation.
- **Manage security alerts** `docs:code-security/tutorials/manage-security-alerts/index.md` — Build skills and knowledge about Github's security and code quality features through examples and hands-on activities.
- **Organizing remediation efforts for leaked secrets** `docs:code-security/tutorials/secure-your-organization/organize-leak-remediation.md` — Systematically organize and manage the remediation of leaked secrets using security campaigns and alert assignments.
- **Preparing for a security incident** `docs:code-security/tutorials/secure-your-organization/prepare-for-a-security-incident.md` — Ensure you have the tools and processes in place to respond effectively to a security incident.
- **Prioritizing Dependabot and code scanning alerts using production context** `docs:code-security/tutorials/secure-your-organization/prioritize-alerts-in-production-code.md` — Focus remediation on real risk by targeting Dependabot and code scanning alerts in artifacts deployed to production, ...
- **Protecting against security threats** `docs:code-security/tutorials/secure-your-organization/protect-against-threats.md` — What steps should I take now, in the near future, and on an ongoing basis
- **Remediate leaked secrets** `docs:code-security/tutorials/remediate-leaked-secrets/index.md` — Learn how to identify and remediate leaked secrets in your codebase.
- **Responding to a security incident** `docs:code-security/tutorials/secure-your-organization/respond-to-a-security-incident.md` — Respond strategically to a security incident affecting organizations or repositories in your Github enterprise.
- **Running a security campaign to fix alerts at scale** `docs:code-security/tutorials/secure-your-organization/best-practice-fix-alerts-at-scale.md` — Launch a focused security campaign to remediate a specific class of security alerts, such as cross-site scripting (XS...
- **Secure your dependencies** `docs:code-security/tutorials/secure-your-dependencies/index.md` — Build skills to help you keep your dependencies up to date and protected from vulnerabilities using automated tools a...
- **Secure your secrets at scale with GitHub** `docs:code-security/tutorials/secret-protection-adoption-path.md` — Leaked credentials expose your organization to data breaches. GitHub Secret Protection detects and prevents secret le...
- **Securing your organization** `docs:code-security/tutorials/secure-your-organization/index.md` — Build skills to help you prevent vulnerabilities and address alerts in your organization.
- **Tutorials for security and code quality** `docs:code-security/tutorials/index.md` — Build skills and knowledge about Github's security and code quality features through examples and hands-on activities.
