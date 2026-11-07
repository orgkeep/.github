Orgkeep makes multi-tenant B2B on Keycloak simple: one **organisation** per customer, **org admins** who manage their
own users and teams, and a catalog of **products** with features and quotas, all in the tokens your APIs already
read. Open source, Apache 2.0.

**Try it in two minutes**, without building anything: `docker compose up` in the demo stack of
[orgkeep-examples](https://github.com/orgkeep/orgkeep-examples/tree/main/docker-compose).

| Repository | What it is |
|---|---|
| [orgkeep-core](https://github.com/orgkeep/orgkeep-core) | The product: the REST API, on top of Keycloak 26. Image `ghcr.io/orgkeep/orgkeep-core` |
| [orgkeep-dashboard](https://github.com/orgkeep/orgkeep-dashboard) | The web UI, with the core embedded: one app. Image `ghcr.io/orgkeep/orgkeep` |
| [orgkeep-theme](https://github.com/orgkeep/orgkeep-theme) | The Keycloak theme: login, emails, Account console. Image `ghcr.io/orgkeep/orgkeep-keycloak` |
| [orgkeep-examples](https://github.com/orgkeep/orgkeep-examples) | The demo stack, and APIs protected by Orgkeep (Spring Boot, Vert.x, a Go gateway) |

[orgkeep.org](https://orgkeep.org) · Contributions welcome: see the `CONTRIBUTING.md` of each repository ·
Security issues: [report them privately](https://github.com/orgkeep/orgkeep-core/security/advisories/new)
