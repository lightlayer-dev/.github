## LightLayer

The infrastructure layer between AI agents and the services they consume.

**Our thesis:** as AI agents become the primary consumers of web services, every API needs identity, payments, discovery, and observability for agent traffic. We're building that stack — open-source middleware, benchmarks, and analytics.

### Projects

🔬 **[agent-bench](https://github.com/LightLayer-dev/agent-bench)** — The standard for AI-agent-readiness scoring. 8 analysis checks, 50+ sites benchmarked across 3 waves, GitHub Action for CI gating, research datasets (robots.txt survey, llms.txt adoption). 178+ tests.

🧱 **[agent-layer-ts](https://github.com/LightLayer-dev/agent-layer-ts)** — Composable TypeScript middleware for Express, Koa, Hono, Fastify, Strapi, and Firestore. 16 modules including x402 payments, A2A Agent Cards, agent identity (IETF draft), MCP server generation, analytics, and more. 613 tests. One line: `app.use(agentLayer())`

🐍 **[agent-layer-python](https://github.com/LightLayer-dev/agent-layer-python)** — Python companion for FastAPI, Flask, and Django. Full feature parity — 12 modules across all three frameworks. 228 tests. One line: `configure_agent_layer(app)`

📊 **[lightlayer-dashboard](https://github.com/LightLayer-dev/lightlayer-dashboard)** — SaaS control plane for agent traffic analytics. Trigger scans, view score breakdowns and trends, ingest agent events. React + FastAPI + Postgres. Production-ready with Docker + Caddy auto-HTTPS.

### What We Build

- **Identity** — Agent credential verification & scoped permissions (IETF draft-klrc-aiagent-auth)
- **Payments** — HTTP-native micropayments via x402 protocol
- **Discovery** — A2A Agent Cards, llms.txt, unified multi-format serving
- **Observability** — Detect 18+ AI agents, collect telemetry, visualize traffic
- **Standards** — agent-bench defines "agent-readiness" like Lighthouse defines "performance"

### Blog & Research

Real data, real benchmarks, no fluff — at [company.lightlayer.dev](https://company.lightlayer.dev)

- [Why Your API Needs an Agent Gateway](https://company.lightlayer.dev/blog/why-your-api-needs-an-agent-gateway.html)
- [We Scored 20 Websites on Agent-Readiness](https://company.lightlayer.dev/blog/we-scored-20-websites-on-agent-readiness.html)
- [Which Sites Block AI Bots — and Which Roll Out the Red Carpet?](https://company.lightlayer.dev/blog/which-sites-block-ai-bots.html)
- [The llms.txt Adoption Report](https://company.lightlayer.dev/blog/llmstxt-adoption-report.html)
- [Do Developer-Focused Sites Practice What They Preach?](https://company.lightlayer.dev/blog/do-devtools-practice-what-they-preach.html)

Research datasets in [agent-bench/research/](https://github.com/LightLayer-dev/agent-bench/tree/main/research) — robots.txt AI bot blocking survey (99 sites) and llms.txt adoption survey (239 sites).
