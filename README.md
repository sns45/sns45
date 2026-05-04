# Shantanu Sharma

Senior Software Engineer building data platforms and agentic developer tooling. Based in Jersey City, NJ.

## About

I lead backend and platform work at **Compass** on systems that power lead generation, ML recommendation pipelines, and CRM integrations for 30,000+ real estate agents. Previously at **WebMD**, building consumer-health platforms and AI chat systems. Outside of work, I build open-source MCP servers and experiment with event-driven AI pipelines on Kubernetes and the latest platform innovations.

## Selected Open Source

**[better-call-claude](https://github.com/sns45/better-call-claude)** — MCP server giving Claude Code bi-directional voice, SMS, and WhatsApp communication, with **cross-channel context sharing** so a conversation can start on a phone call and continue over SMS or WhatsApp. Call Claude from your phone; get callbacks when it needs input.

**[forgeseal](https://github.com/sns45/forgeseal)** — Supply-chain security toolkit for JS/TS, Python, Go, Rust, and Java/Gradle projects. Generates CycloneDX SBOMs from 13 lockfile formats, signs with Sigstore (keyless), produces SLSA provenance attestations, and manages OpenVEX documents. Built for EU Cyber Resilience Act (CRA) compliance.

**[svidmint](https://github.com/sns45/svidmint)** — SPIFFE-compatible workload identity for serverless and edge. Issues X.509 and JWT SVIDs to Lambda, Cloudflare Workers, GitHub Actions, and Deno Deploy via platform-native attestation (STS, Access JWTs, OIDC). The Go SDK is a drop-in replacement for `go-spiffe/v2`'s `workloadapi.NewX509Source()`; the TypeScript SDK runs in Workers via `crypto.subtle`. Federates with SPIRE through standard bundle exchange. If forgeseal is identity for the artifact, svidmint is identity for the runtime.

**[auth-gateway](https://github.com/sns45/auth-gateway)** — Serverless OAuth gateway on Cloudflare Workers with Convex, Better-Auth, and Hono middleware. KV-cached sessions cut service-onboarding time.

**[anyq](https://github.com/sns45/anyq)** — Universal message queue library with a single interface across Redis Streams, SQS/SNS, Pub/Sub, Kafka, RabbitMQ, NATS, and Azure Service Bus. TypeScript-first, with DLQ and circuit breaker built in.

**[dear-claude](https://github.com/sns45/dear-claude)** — Webhook-driven MCP integrations connecting Claude Code to GitHub, Linear, Jira, Notion, and Obsidian.

## Professional Background

**Compass** — Senior Software Engineer (2023 to present), Software Engineer II (2021 to 2023). Built the data pipeline and database infrastructure behind Compass's Likely-to-Sell ML model, which has contributed over **$150MM in incremental revenue since 2021**. Delivered the Likely-to-Win model infrastructure; A/B tests showed a **39% lift in outreach** on new recommendations and a **16% lift** on re-ranked ones. Architected MCP-compliant APIs that integrate **100+ real-estate data sources** into Compass CRM, processing millions of contacts. Leading an **eight-engineer team across four time zones**; work catalyzed **$2M+ quarterly GCI**. Received the *Avengers team player* award in 2022.

**WebMD** — Web Developer progression (2017 to 2021). Led **95% migration** of legacy consumer frontend applications to the Helios platform. Shipped a healthcare AI voice assistant with a **72% answer-success rate** and built the Mucinex chatbot, which generated a multi-million dollar advertising revenue stream on a **$2 CPC** model. Reduced backtesting framework runtime from **14 hours to 1 hour**. Named *Engineer of the Year* (2018) and *Upcoming Leader of the Year* (2019). Oracle Certified Java Professional (scored 98%).

**Platform side project: Watch And Learn (WAL)** — Event-driven multi-agent video-to-markdown pipeline on Kubernetes with LangGraph orchestration. Ongoing sandbox for active-active multi-region IaC, policy-as-code, eBPF observability, and HPA/VPA autoscaling experimentation.

## Education

M.S. Software Engineering, New Jersey Institute of Technology. B.E. Computer Science, Shri Ramdeobaba College of Engineering.

## Current Focus

Model Context Protocol servers, agentic developer tooling, event-driven architecture on Kubernetes, and ML recommendation systems.

## Contact

**Resume:** [shantanu.sh](https://shantanu.sh/?ref=github-readme)
**LinkedIn:** [linkedin.com/in/shantanu-sharma-07](https://www.linkedin.com/in/shantanu-sharma-07)

<!-- View pixel (Cloudflare Worker to PostHog) -->
<img src="https://github-pixel.notifyshantanu.workers.dev/r.gif" width="1" height="1" alt="" />
