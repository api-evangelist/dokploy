# Dokploy (dokploy)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Dokploy is an open-source, self-hostable Platform-as-a-Service (PaaS) — an alternative to Heroku, Vercel, and Netlify — that deploys applications, Docker Compose stacks, and managed databases across one or many servers using Docker and Docker Swarm, with Traefik handling routing and TLS.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dokploy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dokploy/refs/heads/main/apis.yml)

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

- **Human URL:** [https://dokploy.com/](https://dokploy.com/)
- **Base URL:** `https://your-dokploy-instance.com/api`

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
- [API Reference](https://github.com/Dokploy/sdk/blob/main/openapi.json)
- [Getting Started](https://docs.dokploy.com/docs/core)
- [OpenAPI](openapi/dokploy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dokploy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dokploy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [SDK](https://github.com/Dokploy/sdk)
- [C L I](https://github.com/Dokploy/cli)
- [M C P](https://github.com/Dokploy/mcp)
- [Plans](plans/dokploy-plans-pricing.yml)
- [Rate Limits](rate-limits/dokploy-rate-limits.yml)
- [Fin Ops](finops/dokploy-finops.yml)

## Common Properties

- [Website](https://dokploy.com/)
- [Documentation](https://docs.dokploy.com/)
- [API Reference](https://github.com/Dokploy/sdk/blob/main/openapi.json)
- [Pricing](https://dokploy.com/pricing)
- [Git Hub Org](https://github.com/Dokploy)
- [GitHub Repository](https://github.com/Dokploy/dokploy)
- [SDK](https://github.com/Dokploy/sdk)
- [C L I](https://github.com/Dokploy/cli)
- [M C P](https://github.com/Dokploy/mcp)
- [Templates](https://github.com/Dokploy/templates)
- [Examples](https://github.com/Dokploy/examples)
- [Discord](https://discord.gg/2tBnJ3jDJc)
- [License](https://github.com/Dokploy/dokploy/blob/canary/LICENSE.MD)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
