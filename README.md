# Cognee (cognee)

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

- APIs.json: https://raw.githubusercontent.com/api-evangelist/cognee/refs/heads/main/apis.yml
- Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=cognee-api-evangelist&utm_content=repo

## Tags

- AI
- Memory
- Knowledge Graph
- RAG
- Agents
- Graph Database
- Vector Search
- LLM
- Open Source

## APIs

### Cognee REST API

The Cognee REST API provides endpoints for the complete AI memory lifecycle, including data ingestion, knowledge graph construction, and semantic retrieval. Core endpoints cover adding raw text or documents (POST /api/v1/add), triggering the cognify pipeline that extracts entities and relationships via LLM (POST /api/v1/cognify), executing multi-mode search queries (POST /api/v1/search), managing datasets (DELETE /api/v1/datasets), and creating agent identities (/api/v1/agents/*).

- Documentation: https://docs.cognee.ai/api-reference/introduction
- Interactive Docs (Swagger): https://api.cognee.ai/docs
- Base URL: https://api.cognee.ai

## Plans, Rate Limits, and FinOps

- Plans and Pricing: [plans/cognee-plans-pricing.yml](plans/cognee-plans-pricing.yml)
- Rate Limits: [rate-limits/cognee-rate-limits.yml](rate-limits/cognee-rate-limits.yml)
- FinOps: [finops/cognee-finops.yml](finops/cognee-finops.yml)

### Pricing Summary

| Plan | Price | Documents | Users | API Calls/Month |
|---|---|---|---|---|
| Free | $0/month | Unspecified | 1 | Unspecified |
| Developer | $35/month | 1,000 / 1 GB | 1 | 10,000 |
| Cloud (Team) | $200/month | 2,500 / 2 GB | 10 | 10,000 |
| On-Prem (Enterprise) | Custom | Custom | Custom | Custom |

Additional document top-up packs: +1,000 docs for $35, +3,000 docs for $100, +15,000 docs for $750.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|---|---|
| Website | https://www.cognee.ai/ |
| Documentation | https://docs.cognee.ai/ |
| GitHub Org | https://github.com/topoteretes |
| GitHub Repository | https://github.com/topoteretes/cognee |
| LinkedIn | https://www.linkedin.com/company/cognee-ai |
| Blog | https://www.cognee.ai/blog |
| Pricing | https://www.cognee.ai/pricing |
| Cost Calculator | https://www.cognee.ai/cost-calculator |
| X (Twitter) | https://x.com/cognee_ |
| Discord | https://discord.gg/m63hxKsp4p |

## Maintainers

- Kin Lane (kin@apievangelist.com)
