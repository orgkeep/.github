Orgkeep makes multi-tenant B2B on Keycloak simple: one **organisation** per customer, **org admins** who manage their
own users and teams, and a catalog of **products** with features and quotas, all in the tokens your APIs already
read. Open source, Apache 2.0.

**Early preview (0.x)**: ready to be tried, not yet to run in production. Known limitations in the
[README](https://github.com/orgkeep/orgkeep#readme); your feedback is welcome in the issues.

**Try it in two minutes**, without building anything: `docker compose up` in the demo stack of
[orgkeep-examples](https://github.com/orgkeep/orgkeep-examples/tree/main/docker-compose).

| Repository | What it is |
|---|---|
| [orgkeep](https://github.com/orgkeep/orgkeep) | The product, on top of Keycloak 26: the REST API (image `ghcr.io/orgkeep/orgkeep-core`), the web UI with the API embedded (`ghcr.io/orgkeep/orgkeep`), and the Keycloak theme (`ghcr.io/orgkeep/orgkeep-keycloak`) |
| [orgkeep-examples](https://github.com/orgkeep/orgkeep-examples) | The demo stack, and APIs protected by Orgkeep (Spring Boot, Vert.x, a Go gateway) |

[orgkeep.org](https://orgkeep.org) · [Roadmap](https://github.com/orgs/orgkeep/projects/3) · Contributions welcome: see the `CONTRIBUTING.md` of each repository ·
Security issues: [report them privately](https://github.com/orgkeep/orgkeep/security/advisories/new)
