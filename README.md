# Dokploy (dokploy)

Dokploy is an open-source, self-hostable Platform-as-a-Service (PaaS) — an alternative to Heroku, Vercel, and Netlify — that deploys applications, Docker Compose stacks, and managed databases across one or many servers using Docker and Docker Swarm, with Traefik handling routing and TLS.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/dokploy/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- PaaS
- Self-Hosted
- Open Source
- Docker
- Docker Swarm
- Deployment
- Traefik
- Databases

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Dokploy

The Dokploy HTTP API exposes every operation the Dokploy UI can perform — projects, applications, Docker Compose services, managed databases (Postgres, MySQL, MariaDB, MongoDB, Redis, LibSQL), domains, certificates, registries, Git providers (GitHub, GitLab, Gitea, Bitbucket), servers, Docker Swarm clusters, backups, schedules, notifications, audit logs, SSO, custom roles, white-labeling, and Stripe billing — across 526 endpoints generated from the project's canonical OpenAPI 3.1 specification.

**Human URL:** [https://dokploy.com/](https://dokploy.com/)

**Base URL:** `https://your-dokploy-instance.com/api`

Authentication is via an `x-api-key` header generated from **Settings > API Keys** in the Dokploy dashboard.

#### Tags

- PaaS
- Self-Hosted
- Docker
- Docker Swarm
- Traefik
- Deployment
- Databases
- Git Providers
- Domains
- Notifications

#### Properties

- [Documentation](https://docs.dokploy.com/)
- [APIReference](https://github.com/Dokploy/sdk/blob/main/openapi.json)
- [GettingStarted](https://docs.dokploy.com/docs/core)
- [OpenAPI](openapi/dokploy-openapi.yml)
- [SDK](https://github.com/Dokploy/sdk) — `@dokploy/sdk` (TypeScript), auto-generated from the canonical OpenAPI spec.
- [CLI](https://github.com/Dokploy/cli) — `@dokploy/cli`, 449 commands covering every API endpoint.
- [MCP](https://github.com/Dokploy/mcp) — `@dokploy/mcp`, 508 tools across 49 categories, with read-only / destructive / idempotent semantic hints.
- [Plans](plans/dokploy-plans-pricing.yml)
- [RateLimits](rate-limits/dokploy-rate-limits.yml)
- [FinOps](finops/dokploy-finops.yml)

#### Naftiko Capabilities

Each Dokploy business surface is profiled as a self-contained Naftiko 1.0.0-alpha2 capability with `consumes` (HTTP client), `exposes.rest` (REST adapter under `/v1`), and `exposes.mcp` (one tool per operation, with read-only / destructive / idempotent hints).

48 capabilities cover the full surface: admin, ai, application, audit-log, backup, bitbucket, certificates, cluster, compose, custom-role, deployment, destination, docker, domain, environment, git-provider, gitea, github, gitlab, libsql, license-key, mariadb, mongo, mounts, mysql, notification, organization, patch, port, postgres, preview-deployment, project, redirects, redis, registry, rollback, schedule, security, server, settings, ssh-key, sso, stripe, swarm, tag, user, volume-backups, whitelabeling.

## Common Properties

- [Website](https://dokploy.com/)
- [Documentation](https://docs.dokploy.com/)
- [APIReference](https://github.com/Dokploy/sdk/blob/main/openapi.json)
- [Pricing](https://dokploy.com/pricing)
- [GitHubOrg](https://github.com/Dokploy)
- [GitHubRepository](https://github.com/Dokploy/dokploy)
- [SDK](https://github.com/Dokploy/sdk)
- [CLI](https://github.com/Dokploy/cli)
- [MCP](https://github.com/Dokploy/mcp)
- [Templates](https://github.com/Dokploy/templates)
- [Examples](https://github.com/Dokploy/examples)
- [Discord](https://discord.gg/2tBnJ3jDJc)
- [License](https://github.com/Dokploy/dokploy/blob/canary/LICENSE.MD)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
