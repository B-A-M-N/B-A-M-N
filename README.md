# John London — AI Systems & Infrastructure Engineer

**Go · Rust · TypeScript · Python · MCP / ACP · Local & Hybrid Inference**

I build production infrastructure around AI coding agents and inference systems: credential-containment gateways, agent control planes, distributed GPU routing, and security gates.

**Currently available for full-time remote roles or contract engineering** (AI Infrastructure, Agent Systems, Developer Tooling / CLI, AI Security).

<p align="left">
  <a href="https://bamnlanding.lovable.app">Website</a> ·
  <a href="https://x.com/london_joh23108">X / Twitter</a> ·
  <a href="https://ollama.com/B-A-M-N">Ollama</a> ·
  <a href="mailto:benevolentjoker@gmail.com">Email</a>
</p>

- **[gripline](https://github.com/B-A-M-N/gripline)** — credential-containment
  gateway for inference APIs. Terminates reusable API keys at the trust boundary,
  reissues scoped internal assertions, and enforces lanes and hard limits, so a
  key that leaks authorizes less than it appears to. Go, Apache-2.0.
- **[Athena](https://github.com/B-A-M-N/Athena)** — local-first agent runtime built
  around a single authoritative reasoning loop: capability discovery, retained
  evidence, delegated execution, governed multi-runtime operation. Public beta.
  Python, MIT.
- **[Kontrol](https://github.com/B-A-M-N/Kontrol)** — local control plane for web
  and CLI coding agents: MCP workspace access, ACP worker dispatch, human review
  gates. Derived from [Waishnav/devspace](https://github.com/Waishnav/devspace)
  (MIT), extended with worker dispatch, durable review loops, supervised missions,
  and policy approvals. TypeScript, MIT.
- **[AegisKeys](https://github.com/B-A-M-N/AegisKeys)** — Go TUI for key custody
  and provider configuration in coding-agent workflows, with a no-leak render
  check in the release gate. Ships signed releases with cross-platform binaries.
  MIT.

### Verified Upstream Contributions (21+ Merged PRs)

* **[QwenLM/qwen-code](https://github.com/QwenLM/qwen-code)** — 13 merged PRs across core CLI plumbing: unified tool-permission flows, non-blocking auto-memory recall, per-model settings resolution, JSON comment preservation during migrations, and cost estimation.
* **[HarvardMadSys/hybridInference](https://github.com/HarvardMadSys/hybridInference)** — 5 merged PRs (18 submitted) on inference serving internals: fixing storage erasure races under advisory locks, trusted-proxy client-IP resolution, prefill-load-aware routing, and prefix-cache locality validation.
* **[Unity-Lab-AI/ATree](https://github.com/Unity-Lab-AI/ATree)** — Authored the core code-intelligence engine (scope-aware resolution with C3 MRO, multi-language symbol analysis, and MCP server integration).
* **[josstei/maestro-orchestrate](https://github.com/josstei/maestro-orchestrate)** — Added Qwen Code runtime support and refactored single-adapter dispatch into dynamic hook-adapter resolution.

Agent-governance work in progress — behavioral policy, durable state, and
behavioral measurement as separable layers:
[CognitiveFrameWorks](https://github.com/B-A-M-N/CognitiveFrameWorks),
[CognitiveStateWorks](https://github.com/B-A-M-N/CognitiveStateWorks),
[DigitalPsychology](https://github.com/B-A-M-N/DigitalPsychology).

### Selected Production Systems

* **[gripline](https://github.com/B-A-M-N/gripline)** (`Go`) — Credential-containment gateway for inference APIs. Terminates reusable API keys at the trust boundary, issues scoped internal assertions, and enforces hard lanes/limits so leaked keys fail safely.
* **[Kontrol](https://github.com/B-A-M-N/Kontrol)** (`TypeScript`) — Local control plane bridging web AI interfaces and CLI coding agents over MCP/ACP, with worker dispatch, durable review loops, and human approval gates.
* **[AegisKeys](https://github.com/B-A-M-N/AegisKeys)** (`Go`) — Encrypted local key-custody TUI for coding-agent workflows, shipping signed cross-platform binaries with automated no-leak render verification in CI.
* **[SOLLOL](https://github.com/B-A-M-N/SOLLOL)** (`Python / PyPI`) — Load balancer and VRAM-aware router for distributed Ollama clusters with health scoring and automatic failover.

---

### Background

Precision machinist (±0.00015" tolerances) → contract IT → self-taught systems engineering (B.A. Psychology, George Mason). After four years as primary caregiver for my son, I'm ready for full-time or contract engineering work—bringing machinist-grade discipline around deterministic boundaries, failure modes, and shipping reliable tooling under tight constraints.

**Contact:** [benevolentjoker@gmail.com](mailto:benevolentjoker@gmail.com) · [Website](https://bamnlanding.lovable.app) · [X / Twitter](https://x.com/london_joh23108) · [Ollama](https://ollama.com/B-A-M-N)
