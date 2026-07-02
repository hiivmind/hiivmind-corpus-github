# Admin

GitHub Enterprise administration documentation.

> **420 files** | Source: `docs:admin/`

---

## Overview

- **Admin Overview** `docs:admin/index.md` - Enterprise administration guide
- **Getting Started** `docs:admin/get-started/index.md` - Initial setup

- **About user offboarding on GitHub Enterprise Cloud** `docs:admin/concepts/identity-and-access-management/user-offboarding.md` — Manage access with confidence by understanding the recommended approach for offboarding users.
- **Automations in your enterprise** `docs:admin/concepts/enterprise-fundamentals/automations-in-your-enterprise.md` — Learn how Github Apps, external services, and GitHub Actions work together to automate processes in your enterprise.
- **Setup user** `docs:admin/concepts/identity-and-access-management/setup-user.md` — The setup user is used only to configure authentication and provisioning for Emus.
## Enterprise Management

- **Managing Your Enterprise** `docs:admin/managing-your-enterprise/index.md`
- **Enterprise Accounts** `docs:admin/managing-your-enterprise/managing-your-enterprise-account/index.md`
- **Organizations** `docs:admin/managing-your-enterprise/managing-organizations/index.md`

- **Configuring user display names for your enterprise** `docs:admin/managing-your-enterprise-account/configuring-user-display-names-for-your-enterprise.md` — You can choose whether the profile name (first and last name) of your enterprise members appear alongside their usern...
## Identity & Access

- **Authentication** `docs:admin/identity-and-access-management/index.md`
- **SAML SSO** `docs:admin/identity-and-access-management/configuring-saml/index.md`
- **SCIM Provisioning** `docs:admin/identity-and-access-management/provisioning/index.md`
- **Enterprise Managed Users** `docs:admin/identity-and-access-management/enterprise-managed-users/index.md`

- **Locking down single sign-on in your enterprise** `docs:admin/managing-iam/respond-to-incidents/lock-down-sso.md` — Take action in a security incident by blocking SSO for all users except enterprise owners.

- **Migrating from LDAP to SAML with SCIM** `docs:admin/managing-iam/provisioning-user-accounts-with-scim/migrating-from-ldap-to-saml-with-scim.md` — Learn how to migrate your GitHub Enterprise Server instance from LDAP authentication to SAML single sign-on with SCIM...

- **Responding to security incidents in your enterprise** `docs:admin/managing-iam/respond-to-incidents/index.md` — Take bulk action when facing a major security incident.

- **Revoking SSO authorizations or deleting credentials in your enterprise** `docs:admin/managing-iam/respond-to-incidents/revoke-authorizations-or-tokens.md` — Respond to a security incident by taking action on credentials with access to your enterprise.
## Policies

- **Policies** `docs:admin/policies/index.md`
- **Repository Policies** `docs:admin/policies/repository-policies/index.md`
- **Security Policies** `docs:admin/policies/security-policies/index.md`

- **About Actions policies** `docs:admin/enforcing-policies/enforcing-policies-for-your-enterprise/actions-policies/about-actions-policies.md` — Actions policies let you govern how GitHub Actions workflows run across organizations and repositories in your enterp...
- **Actions policies** `docs:admin/enforcing-policies/enforcing-policies-for-your-enterprise/actions-policies/index.md` — Actions policies let you govern how GitHub Actions workflows run across organizations and repositories in your enterp...
- **Workflow execution protections** `docs:admin/enforcing-policies/enforcing-policies-for-your-enterprise/actions-policies/workflow-execution-protections.md` — Workflow execution protections let you control who can trigger GitHub Actions workflows and which events are permitte...
## GitHub Enterprise Server

- **GHES Overview** `docs:admin/enterprise-server/index.md`
- **Installation** `docs:admin/enterprise-server/install/index.md`
- **Configuration** `docs:admin/enterprise-server/configure/index.md`
- **Maintenance** `docs:admin/enterprise-server/maintenance/index.md`
- **Upgrades** `docs:admin/enterprise-server/upgrade/index.md`

- **Migrating GitHub Actions external storage** `docs:admin/managing-github-actions-for-your-enterprise/advanced-configuration-and-troubleshooting/migrating-github-actions-external-storage.md` — Migrate GitHub Actions external storage within the same provider to consolidate accounts, meet residency requirements...
- **Updating the credentials for GitHub Actions storage** `docs:admin/managing-github-actions-for-your-enterprise/advanced-configuration-and-troubleshooting/updating-the-credentials-for-github-actions-storage.md` — If your credentials for connecting to GitHub Actions storage change, you must update the credentials in the configura...

- **Backup from replica in high availability** `docs:admin/backing-up-and-restoring-your-instance/backup-from-replica-in-high-availability.md` — Enable backup from a high availability replica node.

- **Backup in clustering mode** `docs:admin/backing-up-and-restoring-your-instance/backup-in-clustering-mode.md` — Enable backup from a node in cluster.

- **Configuring remote archives for backups** `docs:admin/backing-up-and-restoring-your-instance/configuring-remote-archives-for-backups.md` — Enable a remote archive for backups through SSH.

- **Best practices for configuring API rate limits** `docs:admin/configuring-settings/configuring-user-applications-for-your-enterprise/best-practices-for-configuring-api-rate-limits.md` — A data-driven approach to API rate limits protects your GitHub Enterprise Server instance from excessive usage withou...

- **Enterprise Server Upgrade Automation** `docs:admin/upgrading-your-instance/automation-via-cli-api/enterprise-server-upgrade-automation.md` — You can use the ghes-manage API or `es` plugin to automate upgrade operations in Enterprise Server environments.

- **Rotating the signing key for upgrade packages** `docs:admin/upgrading-your-instance/troubleshooting-upgrades/rotating-the-signing-key-for-upgrade-packages.md` — Learn how to rotate the GPG public key on GitHub Enterprise Server when Company Short updates the key used to sign up...

- **Upgrade Automation With API or CLI** `docs:admin/upgrading-your-instance/automation-via-cli-api/index.md` — You can automate appliance upgrade operation using the ghes-manage API and `es` plugin.
## GitHub Enterprise Cloud

- **GHEC Overview** `docs:admin/enterprise-cloud/index.md`

- **GitHub Copilot with data residency** `docs:admin/data-residency/github-copilot-with-data-residency.md` — Keep AI-powered coding assistance within your designated region, so you can meet compliance requirements while improv...
## Monitoring

- **Monitoring** `docs:admin/monitoring/index.md`
- **Audit Log** `docs:admin/monitoring/audit-log/index.md`

- **About support bundles for GitHub Enterprise Server** `docs:admin/monitoring-and-managing-your-instance/monitoring-your-instance/about-support-bundles.md` — When something goes wrong on your GitHub Enterprise Server instance, a support bundle gives Github Support the diagno...
- **Adding nodes to a high availability configuration** `docs:admin/monitoring-and-managing-your-instance/additional-nodes/configuring-additional-nodes.md` — Add nodes to the primary high availability (HA) datacenter. This is intended to offload CPU-intensive tasks from the ...
- **Additional nodes** `docs:admin/monitoring-and-managing-your-instance/additional-nodes/index.md` — You can configure additional nodes to offload stateless workloads from the primary node in your GitHub Enterprise Ser...
- **Configuring Elasticsearch Cross-Cluster Replication for high availability** `docs:admin/monitoring-and-managing-your-instance/configuring-high-availability/elasticsearch-cross-cluster-replication.md` — You can make search more resilient during maintenance, failovers, and upgrades on a high availability deployment by e...
- **Configuring multiple data disks** `docs:admin/monitoring-and-managing-your-instance/multiple-data-disks/configuring-multiple-data-disks.md` — You can configure additional data disks and use them to host data of different services.
- **Multiple data disks** `docs:admin/monitoring-and-managing-your-instance/multiple-data-disks/index.md` — You can configure additional data disks and use them to host MySQL and repositories data.
- **Using Grafana to analyze OpenTelemetry metrics** `docs:admin/monitoring-and-managing-your-instance/monitoring-your-instance/opentelemetry-metrics/using-grafana-to-analyze-opentelemetry-metrics.md` — Monitor the health and performance of your instance using dashboards and metrics provided by the OpenTelemetry metric...