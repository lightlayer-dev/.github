## LightLayer

Building open-source tools for the AI-agent ecosystem.

**Our thesis:** every website and API should work for AI agents out of the box. We build the tools to make that happen — and the benchmarks to prove it.

### Projects

🔬 **[agent-bench](https://github.com/LightLayer-dev/agent-bench)** — Benchmark suite that scores websites on AI-agent-readiness. Static analysis across 6 dimensions (API surface, docs, auth, structure, errors, cost) plus live agent runs. We scored 20 popular sites — the average was 38%.

🧱 **[agent-layer-ts](https://github.com/LightLayer-dev/agent-layer-ts)** — Composable TypeScript middleware that makes your Express/Fastify/Next.js app agent-friendly. Structured errors, rate limit headers, auto-generated llms.txt, API discovery, and more. One line: `app.use(agentLayer())`

### Blog

We write about what we find. Real data, real benchmarks, no fluff.

- [We Scored 20 Websites on Agent-Readiness](https://company.lightlayer.dev/blog/we-scored-20-websites-on-agent-readiness.html)
- [Building APIs That AI Agents Actually Want to Use](https://company.lightlayer.dev/blog/building-apis-for-ai-agents.html)
- [What Makes a Website AI-Agent-Native?](https://company.lightlayer.dev/blog/what-makes-a-website-ai-agent-native.html)
