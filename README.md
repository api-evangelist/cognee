# Cognee (cognee)

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
