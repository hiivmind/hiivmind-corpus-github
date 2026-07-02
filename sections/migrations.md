# Migrations

Repository migration documentation - importing and migrating to GitHub.

> **69 files** | Source: `docs:migrations/`

---

## Overview

- **Migrations Overview** `docs:migrations/index.md`
- **About Migrations** `docs:migrations/overview/about-github-enterprise-importer.md`

- **About migrations between GitHub products** `docs:migrations/overview/migrations-within-github.md` — Why should I move between Github platforms, and what do I need to consider?
- **Mannequins and user activity** `docs:migrations/overview/mannequins-and-user-activity.md` — Mannequins are placeholder identities that users can reclaim after a migration.

- **Setting ruleset bypasses for repository migrations** `docs:migrations/troubleshooting/setting-ruleset-bypasses-for-repository-migrations.md` — When migrating repositories with Importer Proper Name, evaluation of organization-level and enterprise-level rulesets...

- **Troubleshooting migrations** `docs:migrations/troubleshooting/index.md` — Troubleshoot common issues when migrating repositories with Importer Proper Name.
## Importing Repositories

- **Importing Overview** `docs:migrations/importing-source-code/index.md`
- **Using Importer** `docs:migrations/importing-source-code/using-github-importer.md`
- **From Subversion** `docs:migrations/importing-source-code/importing-from-other-version-control-systems.md`
- **Command Line** `docs:migrations/importing-source-code/using-the-command-line.md`

## GitHub Enterprise Importer

- **GEI Overview** `docs:migrations/using-github-enterprise-importer/index.md`
- **Planning** `docs:migrations/using-github-enterprise-importer/planning-your-migration.md`
- **Migrating from Azure DevOps** `docs:migrations/using-github-enterprise-importer/migrating-from-azure-devops.md`
- **Migrating from Bitbucket** `docs:migrations/using-github-enterprise-importer/migrating-from-bitbucket-server.md`
- **Migrating from GitLab** `docs:migrations/using-github-enterprise-importer/migrating-from-gitlab.md`
- **Between GitHub** `docs:migrations/using-github-enterprise-importer/migrating-between-github-products.md`

- **Follow-up tasks** `docs:migrations/ado/follow-up-tasks.md` — After each migration has finished, you'll need to complete some additional tasks before the repository is ready for w...

- **Granting the migrator role** `docs:migrations/ado/granting-the-migrator-role.md` — The migrator role gives a user or team the ability to run migrations on behalf of an organization.

- **Install and configure GitHub Enterprise Importer** `docs:migrations/ado/install-and-configure-github-enterprise-importer.md` — Install the Ado2Gh Cli and configure your environment for the migration.

- **Key differences between Azure DevOps and GitHub** `docs:migrations/ado/key-differences-between-azure-devops-and-github.md` — Core workflows like repository access, authentication, and pull requests differ after moving from Azure DevOps to Git...

- **Manage access** `docs:migrations/ado/manage-access.md` — Set up the required access for migrating from Azure DevOps to Github.

- **Migrate your repositories from Azure DevOps to GitHub** `docs:migrations/ado/migrate-your-repositories-from-azure-devops-to-github.md` — Perform a trial run and then migrate your repositories from Azure DevOps to Github.

- **Prepare for your migration from Azure DevOps to GitHub** `docs:migrations/ado/prepare-for-your-migration-from-azure-devops-to-github.md` — Plan your migration by understanding your timeline, what data will be migrated, and your organizational structure.

- **Understand migrations from Azure DevOps to GitHub** `docs:migrations/ado/understand-migrations-from-azure-devops-to-github.md` — Importer Proper Name can automate migrating from Azure DevOps.

- **Use GraphQL to migrate repositories from Azure DevOps to GitHub Enterprise Cloud** `docs:migrations/ado/use-graphql-to-migrate-repositories-from-azure-devops-to-github-enterprise-cloud.md` — You can build your own tooling to migrate repositories from Azure DevOps to GitHub Enterprise Cloud using the GraphQL...

- **About live migrations from GitHub Enterprise Server to GHE.com** `docs:migrations/elm/about-live-migrations.md` — How do live migrations minimize downtime for developers?

- **Completing your live migration from GitHub Enterprise Server to GHE.com** `docs:migrations/elm/complete-your-migration.md` — Complete follow-up tasks so users can start using the migrated repository.

- **Enterprise Live Migrations CLI reference** `docs:migrations/elm/elm-cli-reference.md` — Detailed usage information for the Elm Short CLI tool.

- **Live migrations from GitHub Enterprise Server to GHE.com** `docs:migrations/elm/index.md` — Use the Enterprise Live Migrations tool to migrate repositories with minimal downtime for developers.

- **Migrated data for live migrations from GitHub Enterprise Server to GHE.com** `docs:migrations/elm/migrated-data-reference.md` — Which data and live updates are included in a live migration?

- **Migrating your repository with Enterprise Live Migrations** `docs:migrations/elm/migrate-your-repository.md` — Migrate from GitHub Enterprise Server to Data Residency Site with minimal downtime.

- **Preparing for your live migration from GitHub Enterprise Server to GHE.com** `docs:migrations/elm/prepare-for-your-migration.md` — Key questions to consider before getting started with Elm.

- **Troubleshooting live migrations from GitHub Enterprise Server to GHE.com** `docs:migrations/elm/troubleshooting.md` — Advice for problems you may encounter with your migration.
## ghe-migrator

- **ghe-migrator** `docs:migrations/using-ghe-migrator/index.md`
