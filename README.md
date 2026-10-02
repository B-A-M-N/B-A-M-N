# John London

AI systems engineer working on agent runtimes, inference infrastructure, and
developer tooling. Go, Rust, TypeScript, Python.

My work usually sits in the layer between a probabilistic model and something
someone has to sign off on: capability and authority boundaries, durable state,
retained evidence, and the terminal surfaces agents run through.

## Start here

- **[gripline](https://github.com/B-A-M-N/gripline)** — credential-containment
  gateway for inference APIs. Terminates reusable API keys at the trust boundary,
  reissues scoped internal assertions, and enforces lanes and hard limits, so a
  key that leaks authorizes less than it appears to. Go, Apache-2.0.
- **[Athena](https://github.com/B-A-M-N/Athena)** — local-first agent runtime built
  around a single authoritative reasoning loop: capability discovery, retained
  evidence, delegated execution, governed multi-runtime operation. Public beta.
  Python, MIT.
- **[Kontrol](https://github.com/B-A-M-N/Kontrol)** — MCP workspace and ACP bridge
  for observable collaboration between web agent interfaces and CLI coding agents.
  TypeScript, MIT.
- **[tui-lab](https://github.com/B-A-M-N/tui-lab)** — Rust harness for building and
  testing terminal UIs: run lifecycle, event journal, interaction replay, layout
  inspection. Built so a coding agent can develop a TUI without a human at the
  keyboard. MIT.

## Upstream contributions

21 merged PRs into projects maintained by other people.

- **[QwenLM/qwen-code](https://github.com/QwenLM/qwen-code)** — 13 merged:
  auto-memory recall, per-model settings resolution, the shared tool-permission
  flow, settings.json comment preservation, cost estimation, search exit
  semantics.
- **[HarvardMadSys/hybridInference](https://github.com/HarvardMadSys/hybridInference)**
  — 5 merged, 18 total: storage erasure races under advisory locks, trusted-proxy
  client-IP resolution, prefill-load-aware routing, prefix-cache locality
  validation.
- **[Unity-Lab-AI/ATree](https://github.com/Unity-Lab-AI/ATree)** — authored the
  semantic and code-intelligence engine: scope-aware resolution with C3 MRO,
  multi-language symbol analysis, and the MCP integration behind it. That engine
  is most of what ATree became.
- **[josstei/maestro-orchestrate](https://github.com/josstei/maestro-orchestrate)** —
  added Qwen Code as a supported runtime, including the dynamic hook-adapter
  resolution that replaced its single-adapter design, plus a fix for LLM-emitted
  string numbers breaking phase lookups.

## Other systems

- **[SOLLOL](https://github.com/B-A-M-N/SOLLOL)** — load balancing and routing for
  distributed Ollama clusters: node discovery, VRAM- and load-aware placement,
  health scoring, automatic failover. Published on PyPI.
- **[tsmigrate](https://github.com/B-A-M-N/tsmigrate)** — deterministic TypeScript
  6→7 migration engine: ordered transforms, atomic transactions, verification
  oracles, agent escalation over MCP.
- **[Agent-Interop](https://github.com/B-A-M-N/Agent-Interop)** — compatibility
  gateway between coding agents and local or hosted models, with a conformance
  and replay harness for tool calling.
- **[Portico](https://github.com/B-A-M-N/Portico)** — Go connection manager for
  local services and provider-backed tunnels.
- **[GitNexusRelay](https://github.com/B-A-M-N/GitNexusRelay)** — real-time
  code-graph visibility for agents and humans, extending GitNexus.

Agent-governance work in progress — behavioral policy, durable state, and
behavioral measurement as separable layers:
[CognitiveFrameWorks](https://github.com/B-A-M-N/CognitiveFrameWorks),
[CognitiveStateWorks](https://github.com/B-A-M-N/CognitiveStateWorks),
[DigitalPsychology](https://github.com/B-A-M-N/DigitalPsychology).

## Tools

Go · Rust · TypeScript · Python · Kotlin · Bash · MCP · ACP · PyTorch/DDP ·
Ray/Dask · PostgreSQL · Redis · SQLite

## Background

Precision machinist (±0.00015") → contract IT → self-taught systems work.
B.A. Psychology, George Mason. Four years as the primary caregiver for my son,
which is why the work is asynchronous and why I care about agents that hold up
under constraints rather than agents that demo well.

[Website](https://bamnlanding.lovable.app) ·
[Ollama](https://ollama.com/B-A-M-N) ·
[email](mailto:benevolentjoker@gmail.com)