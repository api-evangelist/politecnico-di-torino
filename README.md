# Politecnico di Torino (politecnico-di-torino)

Politecnico di Torino (PoliTO) is Italy's oldest technical university, founded in 1859 in Turin, and a leading European institution for engineering, architecture, and design, ranked #241 in the QS World University Rankings 2025. This repository catalogs its public developer/API footprint as an APIs.json profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/politecnico-di-torino/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=politecnico-di-torino-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Italy
- Open Data
- Mobile
- OpenAPI

## APIs

- **PoliTO REST API (api-spec)** — Official OpenAPI 3.0.3 / TypeSpec specification, the single source of truth for the REST API powering the official students app. Docs: https://github.com/polito/api-spec
- **PoliTO Students App (mobile backend client)** — Official React Native students application (EUPL 1.2) and reference API consumer, configured against `https://app.didattica.polito.it/mock/api`. Docs: https://github.com/polito/students-app
- **PoliTO Open Data** — Institutional open-data portal publishing reusable academic datasets (no documented programmatic API). Docs: https://www.polito.it/open-data

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/politecnico-di-torino-plans-pricing.yml](plans/politecnico-di-torino-plans-pricing.yml)
- Rate Limits: [rate-limits/politecnico-di-torino-rate-limits.yml](rate-limits/politecnico-di-torino-rate-limits.yml)
- FinOps: [finops/politecnico-di-torino-finops.yml](finops/politecnico-di-torino-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.polito.it/en
- GitHub: https://github.com/polito
- LinkedIn: https://it.linkedin.com/school/politecnico-di-torino/
- Open Data: https://www.polito.it/open-data
- Source Code: https://github.com/polito/api-spec
- Review: [review.yml](review.yml)

## Notes

- The @polito GitHub organization is a verified org controlling www.polito.it.
- The PoliTO REST API is documented via an official OpenAPI spec but is consumed by first-party apps; there is no self-service public developer program, public sign-up, or published authentication scheme. No live endpoints were invented.
- `app.didattica.polito.it` is referenced as the API host in the students-app configuration; the `/mock/api` path is a development/mock base.
- The open-data portal exposes downloadable datasets, not a documented API.
- LinkedIn returns HTTP 999 (anti-bot) but the school page loads in a browser. All other URLs returned HTTP 200 on 2026-06-03.

## Maintainers

- Kin Lane — kin@apievangelist.com
