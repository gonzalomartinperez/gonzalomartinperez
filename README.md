# Gonzalo Martin Perez

### Software Engineer | AI Engineer | Product Engineer

I build AI agents, distributed backends, and web and mobile products—from understanding the problem to shipping and operating the solution. My work connects **applied AI with end-to-end product engineering**: useful interfaces, maintainable architecture, measurable performance, testing, observability, and security.

Currently an **AI Engineer at [Rampy](https://getrampy.com/)**, I work directly with three founders on production AI, fintech, and blockchain features. My experience also spans enterprise integrations at [Teamcubation](https://teamcubation.com/) / Payway and [Cooperativa Obrera](https://www.cooperativaobrera.coop/), institutional software, and independent digital products.

**[Portfolio](https://gonzalomartinperez.com/) · [LinkedIn](https://www.linkedin.com/in/gonzalo-martin-perez/) · [English CV](https://gonzalomartinperez.com/cv) · [CV en español](https://gonzalomartinperez.com/es/cv)**

Bahía Blanca, Argentina · **100% remote (UTC−3)** · Spanish: native · English: professional working proficiency (B2)

## Selected work

- **[Rampy](https://gonzalomartinperez.com/work#rampy)** — Built production AI agents with Neo4j GraphRAG: optimized flows ran **at least 2× faster by my estimate**, while removing redundant calls reduced token usage by **an estimated 30% in affected queries**. Reduced comparable vault, market, and perpetual query times **from seconds to milliseconds** using parallel calls, prefetching, and Redis caching.
- **[Teamcubation / Payway](https://gonzalomartinperez.com/work#teamcubation)** — Contributed to event-driven ingestion of **20M+ historical promotions in production** across Python, Java, and Node.js services. Built a merchant-facing GraphRAG assistant with evaluation and data-leakage guardrails; worked with PostgreSQL and MongoDB.
- **[Cooperativa Obrera](https://gonzalomartinperez.com/work#cooperativa-obrera)** — Designed and built a permissions backoffice integrating **10+ enterprise systems**, turning a roughly **10-minute manual lookup into an automated workflow taking under 10 seconds**.
- **[Filomena](https://gonzalomartinperez.com/work/filomena)** — Principal author and contributor in a **three-person team** building an exam platform used by **five Argentine national institutions**. Led architecture, backend, frontend, and infrastructure; the project completed my Information Systems Engineering degree at Universidad Nacional del Sur.

## From product needs to production systems

I connect the user experience with the services, AI workflows, and operational tools behind it. This diagram summarizes patterns from my work across different projects; it is not the deployment architecture of a single employer.

```mermaid
flowchart TB
    UX["Web · Mobile · Backoffice"]
    API["APIs & BFFs<br/>Contracts · Access control"]
    AI["Agent systems<br/>Orchestration · RAG / GraphRAG"]
    SERVICES["Domain services<br/>Business rules · Integrations"]
    CONTEXT["AI context & memory<br/>Vector search · Knowledge graphs"]
    DATA["Data & external providers<br/>Databases · Events · Fintech"]
    OPS["Production delivery<br/>CI/CD · Observability · Evaluation"]
    UX --> API
    API --> AI
    API --> SERVICES
    AI --> CONTEXT
    AI --> SERVICES
    SERVICES --> DATA
    CONTEXT -.-> OPS
    DATA -.-> OPS
    classDef experience fill:#e0f2fe,stroke:#0284c7,color:#0c4a6e;
    classDef application fill:#dbeafe,stroke:#2563eb,color:#1e3a8a;
    classDef foundation fill:#ede9fe,stroke:#7c3aed,color:#4c1d95;
    class UX experience;
    class API,AI,SERVICES application;
    class CONTEXT,DATA,OPS foundation;
```

**Quality throughout the flow:** user-centered design, clear domain boundaries, performance measured on comparable workloads, automated tests, agent evaluations, and security guardrails.

[See the project-specific architectures and outcomes](https://gonzalomartinperez.com/work)

## Engineering toolkit

A selection from my professional work, projects, and broader hands-on experience. [Explore the full stack and its project evidence](https://gonzalomartinperez.com/stack)

**AI & agents**

![LangChain](https://img.shields.io/badge/LangChain-20232A?style=flat-square&logo=langchain) ![LangGraph](https://img.shields.io/badge/LangGraph-20232A?style=flat-square&logo=langgraph) ![Neo4j](https://img.shields.io/badge/Neo4j-F4F5F7?style=flat-square&logo=neo4j) ![MCP](https://img.shields.io/badge/MCP-F4F5F7?style=flat-square&logo=modelcontextprotocol&logoColor=000000) ![OpenAI API](https://img.shields.io/badge/OpenAI%20API-F4F5F7?style=flat-square&logoColor=000000) ![Agno](https://img.shields.io/badge/Agno-2563EB?style=flat-square)

**Languages & backend**

![Python](https://img.shields.io/badge/Python-F4F5F7?style=flat-square&logo=python) ![TypeScript](https://img.shields.io/badge/TypeScript-F4F5F7?style=flat-square&logo=typescript) ![Java](assets/java.svg) ![Node.js](https://img.shields.io/badge/Node.js-F4F5F7?style=flat-square&logo=nodedotjs) ![FastAPI](https://img.shields.io/badge/FastAPI-F4F5F7?style=flat-square&logo=fastapi) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-F4F5F7?style=flat-square&logo=springboot) ![NestJS](https://img.shields.io/badge/NestJS-F4F5F7?style=flat-square&logo=nestjs&logoColor=E0234E) ![Laravel](https://img.shields.io/badge/Laravel-F4F5F7?style=flat-square&logo=laravel) ![Solidity](https://img.shields.io/badge/Solidity-F4F5F7?style=flat-square&logo=solidity&logoColor=363636)

**Web & mobile**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react) ![Next.js](https://img.shields.io/badge/Next.js-F4F5F7?style=flat-square&logo=nextdotjs&logoColor=000000) ![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react) ![Kotlin](https://img.shields.io/badge/Kotlin-F4F5F7?style=flat-square&logo=kotlin) ![Swift](https://img.shields.io/badge/Swift-F4F5F7?style=flat-square&logo=swift)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-F4F5F7?style=flat-square&logo=postgresql) ![pgvector](https://img.shields.io/badge/pgvector-F4F5F7?style=flat-square&logo=postgresql) ![MongoDB](https://img.shields.io/badge/MongoDB-F4F5F7?style=flat-square&logo=mongodb) ![MySQL](https://img.shields.io/badge/MySQL-F4F5F7?style=flat-square&logo=mysql) ![Redis](https://img.shields.io/badge/Redis-F4F5F7?style=flat-square&logo=redis)

**Cloud, delivery & observability**

![AWS](assets/aws.svg) ![Docker](https://img.shields.io/badge/Docker-F4F5F7?style=flat-square&logo=docker) ![Kubernetes](https://img.shields.io/badge/Kubernetes-F4F5F7?style=flat-square&logo=kubernetes) ![DigitalOcean](https://img.shields.io/badge/DigitalOcean-F4F5F7?style=flat-square&logo=digitalocean) ![Coolify](https://img.shields.io/badge/Coolify-F4F5F7?style=flat-square&logo=coolify&logoColor=6B16ED) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-F4F5F7?style=flat-square&logo=githubactions) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-F4F5F7?style=flat-square&logo=opentelemetry&logoColor=000000) ![Prometheus](https://img.shields.io/badge/Prometheus-F4F5F7?style=flat-square&logo=prometheus) ![Grafana](https://img.shields.io/badge/Grafana-F4F5F7?style=flat-square&logo=grafana)

**Applied AI:** Generative AI and LLMs; RAG / GraphRAG; context and prompt engineering; embeddings and chunking; AI testing, evaluation, and guardrails; fine-tuning and LLMOps. I work with OpenAI API, Claude API, Agno, and pgvector alongside the tools above.

**Experience scope:** Solidity reflects limited hands-on work at Rampy. Infrastructure work includes DigitalOcean deployments; AWS and Kubernetes experience centers on application development, integration, and diagnosis.

**Production engineering:** Hexagonal, layered, and event-driven architecture; REST APIs and BFFs; design systems; SQL tuning; AWS Lambda, S3, SQS, and API Gateway; CI/CD, access control, and end-to-end encryption. My broader infrastructure experience also includes Coolify and reverse proxies.

**Fintech integrations:** Morpho, Aave, Compound, Hyperliquid, LI.FI, Privy, and Stripe—across product interfaces, backend services, wallets, and transaction flows.

## Let’s build something useful

I’m open to **100% remote software, AI, and product engineering opportunities**, including backend and full-stack roles, and available for interviews.

[Get in touch](https://gonzalomartinperez.com/contact) · [Browse my experience](https://gonzalomartinperez.com/work) · [Portfolio en español](https://gonzalomartinperez.com/es/)
