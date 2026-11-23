# John London | AI Infrastructure & Agent Systems Engineer

**Go · Rust · Python · TypeScript · Inference gateways · MCP / ACP · Security & reliability**

I design and build infrastructure that makes AI agents and inference services **controllable, recoverable, and safe to operate**: admission and capacity control, durable agent workflows, scoped credentials, human approval boundaries, and local-first tooling.

I work across implementation, incident diagnosis, test qualification, and release engineering—not just model integration.

**Open to remote AI infrastructure, agent-platform, developer tooling, and security engineering roles and contracts.**

[Website](https://bamnlanding.lovable.app) · [Email](mailto:bamn.labs.ai@gmail.com) · [Ollama](https://ollama.com/B-A-M-N) · [X](https://x.com/london_joh23108)

---

## Open-source contributions

**90+ merged pull requests in external repositories** are visible in the current GitHub merged-PR search results alone, with contributions spanning production inference services, cloud-agent lifecycle, and coding-agent security. See [merged PRs](https://github.com/pulls?q=is%3Apr+is%3Amerged+author%3AB-A-M-N+-user%3AB-A-M-N) for the source of truth.

| Ecosystem | Selected work |
| --- | --- |
| **[HarvardMadSys / hybridInference](https://github.com/HarvardMadSys/hybridInference)** | Inference routing and serving correctness; explicit cache-usage evidence; backend modularization; authenticated request accounting; failure and backpressure handling. [Cache evidence](https://github.com/HarvardMadSys/hybridInference/pull/1670) · [Backend decomposition](https://github.com/HarvardMadSys/hybridInference/pull/1626) · [Serving performance](https://github.com/HarvardMadSys/hybridInference/pull/1675) |
| **[HarvardMadSys / cloud-agent](https://github.com/HarvardMadSys/cloud-agent)** | Run/worker lifecycle, grants and access boundaries, query efficiency, recovery, and compute safeguards. [Scoped usage ledger](https://github.com/HarvardMadSys/cloud-agent/pull/842) · [Host-release guards](https://github.com/HarvardMadSys/cloud-agent/pull/986) · [Command resolver](https://github.com/HarvardMadSys/cloud-agent/pull/1125) |
| **[xanstomper / mochi](https://github.com/xanstomper/mochi)** | Dozens of merged fixes in tool safety, approval enforcement, durable background work, checkpoint recovery, patch containment, output redaction, and execution lifecycle. [Approval bypass fix](https://github.com/xanstomper/mochi/pull/21) · [Checkpoint rollback](https://github.com/xanstomper/mochi/pull/24) · [Output-policy replay gate](https://github.com/xanstomper/mochi/pull/55) |
| **[QwenLM / qwen-code](https://github.com/QwenLM/qwen-code)** | CLI tool-permission handling, memory recall, per-model settings, configuration migration, and cost estimation. [Repository](https://github.com/QwenLM/qwen-code) |
| **[Unity-Lab-AI / ATree](https://github.com/Unity-Lab-AI/ATree)** | Collaborative Rust code-intelligence engine: multi-language symbol analysis, scope-aware resolution, graph queries, and MCP integration. [Project](https://github.com/Unity-Lab-AI/ATree) |

**Ongoing engineering:** [HybridInference PRs](https://github.com/HarvardMadSys/hybridInference/pulls?q=is%3Apr+author%3AB-A-M-N) and [cloud-agent PRs](https://github.com/HarvardMadSys/cloud-agent/pulls?q=is%3Apr+author%3AB-A-M-N). Submitted or in-review work is not represented as merged.

---

## Systems I've built

| Project | Engineering scope |
| --- | --- |
| **[Gripline](https://github.com/B-A-M-N/gripline)** · Go | Credential-containment gateway: reusable external secrets stop at the boundary; signed, short-lived internal assertions and deterministic policy enforce scoped downstream access. Public beta. |
| **[Kontrol](https://github.com/B-A-M-N/Kontrol)** · TypeScript | Self-hosted MCP/ACP control plane for local coding agents: worker dispatch, transactional workflow state, durable review/continuation records, and per-tool/per-path human approval gates. |
| **[Ocliv](https://github.com/B-A-M-N/ocliv)** · Go | Self-hosted, outbound-only publishing of local MCP services through authenticated tunnels; stable HTTPS identity, managed OAuth 2.1, and revocable access. Linux-focused v0.1. |
| **[AegisKeys](https://github.com/B-A-M-N/AegisKeys)** · Go | Local encrypted secret custody with Argon2id + AES-256-GCM, provider profiles, policy-aware launch adapters, child-process-scoped credential injection, and terminal UI. |
| **[Locus](https://github.com/B-A-M-N/Locus)** · Python | Local provider-aware inference gateway coordinating admission, concurrency, retries, usage accounting, and provider routing under bounded capacity. Qualification evidence is documented in-repo. |
| **[SOLLOL](https://github.com/B-A-M-N/SOLLOL)** · Python | Ollama-compatible multi-node inference routing with health checks, load/capacity scoring, observability, and failover. [PyPI package](https://pypi.org/project/sollol/). |
| **[Athena](https://github.com/B-A-M-N/Athena)** · Python / Rust | Local-first agent runtime with durable knowledge, governed execution, structured delegation, and evidence-based capability development. Beta candidate, not a stable release. |

These are different systems at different maturity levels; their repositories document current release status, tests, and limitations. Architecture claims are not a substitute for independently verified production deployment.

---

## What I focus on

- **Inference infrastructure:** admission control, rate/capacity budgets, streaming correctness, cache-locality evidence, health assessment, graceful degradation, and recovery.
- **Agent systems:** MCP/ACP interoperability, durable execution state, delegation, handoffs, human-in-the-loop approvals, and reproducible qualification.
- **Security engineering:** scoped authority, credential isolation, path/tool containment, auditability, revocation, and fail-closed design.
- **Systems implementation:** Go and Rust services, Python backends, TypeScript control planes, terminal applications, Linux deployment and diagnostics.

## Background

I came to software through precision machining and hands-on IT work. Working to tight manufacturing tolerances shaped how I approach engineering: verify the boundary conditions, understand failure modes, measure behavior, and make changes reproducible. I also hold a B.A. in Psychology, a useful complement when designing systems where human decisions and automated agents intersect.

**Contact:** [bamn.labs.ai@gmail.com](mailto:bamn.labs.ai@gmail.com) · [Website](https://bamnlanding.lovable.app)
