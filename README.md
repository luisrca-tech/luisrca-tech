<p align="center">
  <img
    src="https://raw.githubusercontent.com/luisrca-tech/luisrca-tech/main/assets/pipeline.svg"
    width="100%"
    alt="Production request pipeline: a request flows from client to a Hono edge API, into a RAG pipeline on pgvector with a semantic cache, out to a multi-provider LLM router (OpenAI, Anthropic, Groq) and back to the client. AI latency and cost both reduced 66%. 300+ projects orchestrated at ~68% margin."
  >
</p>

<h1 align="center">Luis Felipe Da Rocha</h1>

<p align="center">
  <strong>Full Stack / AI Engineer · SaaS Architect</strong><br>
  Goiânia, Brazil · Remote · open to full-time, contract and freelance
</p>

<p align="center">
  <a href="https://luisrca-tech.vercel.app/">Portfolio</a> ·
  <a href="https://luisrca-tech.vercel.app/Luis-Felipe-CV.pdf">CV</a> ·
  <a href="https://www.linkedin.com/in/luisfelipedarocha/">LinkedIn</a> ·
  <a href="mailto:luisrochacruzalves@gmail.com">Email</a>
</p>

> I build production systems where the architecture decision is the business outcome.
> AI is an instrument under engineering control — not autopilot.

## Verified impact

- **300+ projects** running through a stage-based 3D-rendering production pipeline I architected — at a **~68% profit margin**, audited to the cent against production data with **0 divergences**
- **−66% AI latency and cost** — rebuilt a single-provider OpenAI integration into a multi-model RAG orchestrator with semantic caching, chunking and context reuse
- **+40% scalability** by splitting a monolith into specialized Node.js and Python microservices
- **Junior → Mid-Level in 6 months** at Naranja Labs, on architecture impact and technical leadership

## Building

**DeliveryChat** — multi-tenant chat-as-a-service &nbsp;·&nbsp; [code](https://github.com/luisrca-tech/DeliveryChat) &nbsp;·&nbsp; [case study](https://luisrca-tech.vercel.app/projects/deliverychat/)
<br>Embeddable real-time widget plus an operator dashboard, as one type-safe Turborepo monorepo. Room-based WebSocket manager with race-safe operator assignment, Shadow DOM widget isolation, per-tenant Postgres isolation by subdomain, Better Auth RBAC across three tiers, Stripe subscription gating.
<br>`TypeScript` `Hono` `WebSocket` `Drizzle` `React 19` `Better Auth` `Stripe` `Cloudflare Workers` `Bun`

**AI Real-Estate Site Builder** — multi-tenant SaaS &nbsp;·&nbsp; [case study](https://luisrca-tech.vercel.app/projects/ai-site-builder/) &nbsp;·&nbsp; *client work, source private*
<br>Generates marketing websites from uploaded documents and voice input. Multi-model RAG orchestration behind decoupled microservices for cost control and provider flexibility.
<br>`Python` `FastAPI` `RAG` `pgvector` `LangChain` `Multi-LLM` `Whisper` `Next.js`

**Render Delivery Platform** — internal production platform &nbsp;·&nbsp; [case study](https://luisrca-tech.vercel.app/projects/render-delivery-platform/) &nbsp;·&nbsp; *client work, source private*
<br>Runs a US studio's 3D-rendering pipeline end-to-end: client proposals → clay and colour drafts → final renders → delivery and billing. Decoupled hook architecture, RBAC, and a standalone read-only audit harness that verifies every financial KPI against production data.
<br>`TypeScript` `NestJS` `Next.js` `PostgreSQL` `Drizzle` `RBAC` `Stripe` `Sentry`

**Attios-CRM** — full-stack multi-tenant CRM &nbsp;·&nbsp; [code](https://github.com/luisrca-tech/Attios-CRM)
<br>Built to sell rather than to demo: subscription billing, per-tenant data isolation and role-based access from the first commit.
<br>`TypeScript` `Next.js` `PostgreSQL` `Prisma` `Docker`

More at **[luisrca-tech.vercel.app](https://luisrca-tech.vercel.app/)**.

## Stack

| | |
|---|---|
| **Languages** | `TypeScript` `JavaScript` `Python` `SQL` |
| **Frontend** | `Next.js` `React 19` `Astro` `TailwindCSS` `shadcn/ui` `Radix` `TanStack` |
| **Backend** | `Node.js` `NestJS` `Hono` `tRPC` `FastAPI` `WebSocket` `gRPC` `Redis` `RabbitMQ` |
| **Data** | `PostgreSQL` `pgvector` `Drizzle` `Prisma` `Supabase` `Zod` |
| **AI** | `RAG` `Multi-LLM orchestration` `LangChain` `LangGraph` `OpenAI` `OpenRouter` `Groq` `Vector embeddings` `Semantic caching` |
| **Platform** | `Docker` `Turborepo` `Bun` `AWS` `Cloudflare Workers` `Vercel` `CI/CD` `Sentry` `PostHog` |
| **Testing** | `TDD` `Vitest` `Jest` `Playwright` `Pytest` |

## How I work

Spec-driven development with an agentic toolchain — Cursor, Claude Code, CLI agents — using agentic looping, custom skills and sub-agents to compress multi-service roadmaps. Every output reviewed, scope held, nothing unsafe reaching production. Underneath it: TDD, type-safe APIs, clean architecture.

---

<sub>Associate of Science in Systems Analysis and Development — Senac São Paulo, 2024–2026 · English (advanced) · Portuguese (native) · French (basic)</sub>
