# Politecnico di Torino

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Politecnico di Torino (PoliTO) is Italy's oldest technical university, founded in Turin in 1859, with roughly 38,000 students across engineering, architecture and design. Unusually for this cohort, its programmable footprint is genuinely its own rather than a vendor's: the university publishes the OpenAPI definition of the REST API behind its official student and faculty mobile applications in the verified @polito GitHub organisation (polito/api-spec, authored in TypeSpec and emitted as two client contracts, Polito Faculty API and Polito Students API), and the React Native apps that consume it are open-sourced under EUPL-1.2 in polito/rn-apps and polito/students-app. That API runs on the university's own host, app.didattica.polito.it, and covers announcements, authentication with MFA, room and slot bookings, courses, lectures, news, people, places, exams, grades, degree offering, job offers, surveys, support tickets and the European Student Card. It is not a self-service developer programme: the production base path returns 403 to an anonymous caller, every operation is bearer authenticated against a PoliTO account, and no key can be requested by an outsider. Two further institution-operated machine-readable surfaces exist and are recorded here for the first time — a Shibboleth SAML 2.0 identity provider registered in IDEM GARR and eduGAIN since 2020, and an OAI-PMH 2.0 harvesting service over the IRIS research repository, the latter a CINECA tenant deployment rather than PoliTO engineering. A fourth institution-operated surface was found on 2026-08-30 and is the only one an outsider can actually call: four keyless JSON web services behind the polito.it site search — staff, departments and teachings at mypoli.polito.it/dotnet/ws_anagrafe and a campus room locator at legacyprod.polito.it — all returning HTTP 200 and real data with no credential, on hosts inside the university's own GARR address space. They are undocumented and unversioned, PoliTO does not present them as a developer product, and the OpenAPI held here is derived from probing rather than published. The university also runs HPC@PoliTO, an academic computing service managed in-house, whose allocation process is entirely by email with no programmatic surface. The institutional open-data portal publishes downloadable datasets only, with no API behind it, and there is no data.polito.it or api.polito.it host in service.

**Areas:** Education · Higher Education · University · Technical University · Italy · Course Catalog · Research Data · Identity Federation · Open Data · Mobile · OpenAPI

## Politecnico di Torino on APIs.io

Everything profiled for Politecnico di Torino is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/politecnico-di-torino/](https://apis.io/providers/politecnico-di-torino/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [PoliTO Students App (mobile backend client)](https://apis.io/apis/politecnico-di-torino/students-app/) — Politecnico di Torino's official React Native mobile applications for students and faculty, open-sourced under EUPL-1.2 in the verified @polito GitHub…
- [PoliTO Open Data](https://apis.io/apis/politecnico-di-torino/open-data/) — Institutional open-data portal publishing freely reusable academic datasets — study programmes and courses, student enrolment, international students,…
- [Politecnico di Torino Shibboleth Identity Provider (IDEM GARR / eduGAIN)](https://apis.io/apis/politecnico-di-torino/identity-federation/) — Machine-readable SAML 2.0 identity-provider metadata for Politecnico di Torino, served from the university's own address space at idp.polito.it…
- [IRIS PoliTO OAI-PMH Metadata Service (CINECA deployment)](https://apis.io/apis/politecnico-di-torino/iris-oai/) — OAI-PMH 2.0 harvesting service over IRIS, Politecnico di Torino's institutional research repository, reachable at https://iris.polito.it/oai/request.…
- [Politecnico di Torino Announcements API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-announcements-api/) — Announcements resources of the Polito Faculty API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino Auth API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-auth-api/) — Auth resources of the Polito Faculty API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the contract…
- [Politecnico di Torino Bookings API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-bookings-api/) — Bookings resources of the Polito Faculty API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino Courses API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-courses-api/) — Courses resources of the Polito Faculty API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino Esc API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-esc-api/) — Esc resources of the Polito Students API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the contract…
- [Politecnico di Torino Exams API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-exams-api/) — Exams resources of the Polito Students API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino Job offers API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-job-offers-api/) — Job Offers resources of the Polito Students API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino Lectures API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-lectures-api/) — Lectures resources of the Polito Faculty API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino News API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-news-api/) — News resources of the Polito Faculty API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the contract…
- [Politecnico di Torino Offering API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-offering-api/) — Offering resources of the Polito Students API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino People API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-people-api/) — People resources of the Polito Faculty API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino Places API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-places-api/) — Places resources of the Polito Faculty API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino Student API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-student-api/) — Student resources of the Polito Students API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino Surveys API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-surveys-api/) — Surveys resources of the Polito Students API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino Tickets API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-tickets-api/) — Tickets resources of the Polito Students API, split per tag from openapi/_original/. Operated by Politecnico di Torino on app.didattica.polito.it; the…
- [Politecnico di Torino Campus API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-campus-api/) — Campus building and room lookup.
- [Politecnico di Torino Directory API](https://apis.io/apis/politecnico-di-torino/politecnico-di-torino-directory-api/) — People, department and teaching lookup behind the polito.it site search.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Politecnico Di Torino Agentic Access](https://apis.io/agentic-access/politecnico-di-torino/politecnico-di-torino-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Announcement](https://apis.io/schemas/politecnico-di-torino/politecnico-di-torino-announcement/)
- [Booking](https://apis.io/schemas/politecnico-di-torino/politecnico-di-torino-booking/)
- [Exam](https://apis.io/schemas/politecnico-di-torino/politecnico-di-torino-exam/)
- [Student](https://apis.io/schemas/politecnico-di-torino/politecnico-di-torino-student/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Politecnico Di Torino Exam Structure](https://apis.io/json-structure/politecnico-di-torino/politecnico-di-torino-exam-structure/)
- [Politecnico Di Torino Student Structure](https://apis.io/json-structure/politecnico-di-torino/politecnico-di-torino-student-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Politecnico Di Torino Context](https://apis.io/jsonld/politecnico-di-torino/politecnico-di-torino-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Politecnico di Torino API Vocabulary](https://apis.io/vocabularies/politecnico-di-torino/politecnico-di-torino-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Politecnico Di Torino Getannouncements Example](https://apis.io/examples/politecnico-di-torino/politecnico-di-torino-getAnnouncements-example/)
- [Politecnico Di Torino Getexams Example](https://apis.io/examples/politecnico-di-torino/politecnico-di-torino-getExams-example/)
- [Politecnico Di Torino Getstudent Example](https://apis.io/examples/politecnico-di-torino/politecnico-di-torino-getStudent-example/)

#### Collections (15)

Postman and Open Collection request collections.

- [Polito Faculty API — Announcements](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-announcements-api/)
- [Polito Faculty API — Auth](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-auth-api/)
- [Polito Faculty API — Bookings](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-bookings-api/)
- [Polito Faculty API — Courses](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-courses-api/)
- [Polito Students API — Esc](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-esc-api/)
- [Polito Students API — Exams](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-exams-api/)
- [Polito Students API — Job offers](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-job-offers-api/)
- [Polito Faculty API — Lectures](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-lectures-api/)
- [Polito Faculty API — News](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-news-api/)
- [Polito Students API — Offering](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-offering-api/)
- [Polito Faculty API — People](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-people-api/)
- [Polito Faculty API — Places](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-places-api/)
- [Polito Students API — Student](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-student-api/)
- [Polito Students API — Surveys](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-surveys-api/)
- [Polito Students API — Tickets](https://apis.io/collections/politecnico-di-torino/open-politecnico-di-torino-tickets-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Politecnico di Torino — jsonschema rules](https://apis.io/rules/politecnico-di-torino/politecnico-di-torino-jsonschema-spectral-rules/)
- [Politecnico di Torino API Rules](https://apis.io/rules/politecnico-di-torino/politecnico-di-torino-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Politecnico Di Torino Authentication](https://apis.io/security/politecnico-di-torino/politecnico-di-torino-authentication/)
- [Politecnico Di Torino Domain Security](https://apis.io/security/politecnico-di-torino/politecnico-di-torino-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Politecnico Di Torino Plans Pricing](https://apis.io/plans/politecnico-di-torino/politecnico-di-torino-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Politecnico Di Torino Rate Limits](https://apis.io/rate-limits/politecnico-di-torino/politecnico-di-torino-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Politecnico Di Torino Finops](https://apis.io/finops/politecnico-di-torino/politecnico-di-torino-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.polito.it/en)
- [Documentation](https://github.com/polito/api-spec)
- [Privacy policy](https://www.polito.it/en/privacy)

## API Evangelist rating

**Kin Score 37.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 51.7 |
| Contract governance | 13.6 |
| Operational transparency | 36.8 |
| Developer ergonomics | 21.4 |
| Access clarity | 15.8 |

**Agent readiness 27.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/politecnico-di-torino/](https://apis.io/providers/politecnico-di-torino/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Politecnico di Torino: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/politecnico-di-torino/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
