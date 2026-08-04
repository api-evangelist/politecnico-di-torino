# Politecnico di Torino (politecnico-di-torino)

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
