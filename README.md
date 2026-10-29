# Cognee

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

Cognee is an open-source AI memory and knowledge graph platform that enables developers to build persistent, structured memory for AI agents and LLM applications. The platform provides a REST API and Python/TypeScript SDKs for ingesting documents and data from 28+ sources, processing them through a six-stage ECL (Extract, Cognify, Load) pipeline, and storing the resulting entities and relationships in a hybrid graph-vector-relational store. Developers can query the knowledge graph using 13+ search modes including semantic graph completion, RAG completion, and temporal search. Cognee is available as a managed cloud service on AWS, GCP, and Azure, or as a self-hosted deployment via Docker, Modal, Railway, Fly.io, and Render.

**Areas:** Artificial Intelligence · Memory · Knowledge Graph · RAG · Agents · Graph Database · Vector Search · LLM · Open Source

## Cognee on APIs.io

Everything profiled for Cognee is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cognee/](https://apis.io/providers/cognee/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Cognee Agents API](https://apis.io/apis/cognee/cognee-agents-api/) — AI agent identity management
- [Cognee Cognify API](https://apis.io/apis/cognee/cognee-cognify-api/) — Knowledge graph construction pipeline
- [Cognee Data API](https://apis.io/apis/cognee/cognee-data-api/) — Data ingestion and deletion operations
- [Cognee Datasets API](https://apis.io/apis/cognee/cognee-datasets-api/) — Dataset management and introspection
- [Cognee Health API](https://apis.io/apis/cognee/cognee-health-api/) — Service health probes
- [Cognee Search API](https://apis.io/apis/cognee/cognee-search-api/) — Semantic and graph search queries
- [Cognee Settings API](https://apis.io/apis/cognee/cognee-settings-api/) — System configuration (LLM and vector DB)

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cognee Agentic Access](https://apis.io/agentic-access/cognee/cognee-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Cognee Dataset](https://apis.io/schemas/cognee/cognee-dataset/)
- [Cognee Search Payload](https://apis.io/schemas/cognee/cognee-search-payload/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cognee Context](https://apis.io/jsonld/cognee/cognee-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cognee API Vocabulary](https://apis.io/vocabularies/cognee/cognee-vocabulary/)

#### Examples (1)

Example requests and responses.

- [Cognee Search Example](https://apis.io/examples/cognee/cognee-search-example/)

#### Collections (7)

Postman and Open Collection request collections.

- [Cognee REST agents API](https://apis.io/collections/cognee/open-cognee-agents-api/)
- [Cognee REST agents cognify API](https://apis.io/collections/cognee/open-cognee-cognify-api/)
- [Cognee REST agents data API](https://apis.io/collections/cognee/open-cognee-data-api/)
- [Cognee REST agents datasets API](https://apis.io/collections/cognee/open-cognee-datasets-api/)
- [Cognee REST agents health API](https://apis.io/collections/cognee/open-cognee-health-api/)
- [Cognee REST agents search API](https://apis.io/collections/cognee/open-cognee-search-api/)
- [Cognee REST agents settings API](https://apis.io/collections/cognee/open-cognee-settings-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Cognee — jsonschema rules](https://apis.io/rules/cognee/cognee-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cognee Authentication](https://apis.io/security/cognee/cognee-authentication/)
- [Cognee Domain Security](https://apis.io/security/cognee/cognee-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cognee Plans Pricing](https://apis.io/plans/cognee/cognee-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cognee Rate Limits](https://apis.io/rate-limits/cognee/cognee-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cognee Finops](https://apis.io/finops/cognee/cognee-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cognee.ai/)
- [Documentation](https://docs.cognee.ai/)
- [Pricing](https://www.cognee.ai/pricing)
- [Blog](https://www.cognee.ai/blog)

## API Evangelist rating

**Kin Score 42.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 53.2 |
| Contract governance | 23.5 |
| Operational transparency | 36.8 |
| Developer ergonomics | 28.6 |
| Access clarity | 18.4 |

**Agent readiness 25.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
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
| Pagination Ratio | — |
| Operation Distinctiveness | mostly |

**Regulatory alignment 15.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cognee/](https://apis.io/providers/cognee/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cognee: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cognee/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
