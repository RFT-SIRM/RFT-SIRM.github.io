# RFT-SIRM.github.io

> **Live site:** [https://rft-sirm.github.io](https://rft-sirm.github.io)

Public research platform for the **RFT-SIRM Laboratory** — Deterministic Invariant Systems Research.

---

## What is this?

This repository hosts the official landing page for the RFT-SIRM research laboratory. The site is built as a single-page static application deployed via **GitHub Pages**.

Every claim, metric, and result on the site is traceable from model to evidence.

---

## Sections

| Section | Description |
|---------|-------------|
| **Pipeline** | Interactive research pipeline: Claim → Model → Execution → Verification → Evidence → Reproduction |
| **SIRM** | Interactive State Machine transition flow (hover for specs) |
| **Invariants** | I1–I4 hard constraints with full technical specifications |
| **Evidence Center** | 1T+ ops, 4.29B+ contexts, 91M scheduler runs — every number has provenance |
| **Claims Registry** | Traceable claims with status: Validated / Implemented / Experimental / Research / Planned |
| **Verification Matrix** | L1 (Static) → L2 (Tests) → L3 (Fuzz) → L3b (Kernel) → L3c (DeFi) → L4 (Formal) |
| **Case Studies** | Aave V4 Hub, Agave Scheduler, ABIv2 Memory, seL4 CDT, Rift-L1 & Network |
| **AI Research** | Roadmap: deterministic agents, invariant-preserving workflows, reproducible inference |
| **Timeline** | Completed / Active / Planned milestones |
| **Glossary 2.0** | 14 precise definitions with expandable technical details |

---

## Core Repositories

- [Rift-L1-Blockchain](https://github.com/RFT-SIRM/Rift-L1-Blockchain) — Standalone validator core, 1T+ fuzzed ops
- [Rift-Network](https://github.com/RFT-SIRM/Rift-Network) — Solana/Anchor on-chain protocol, RC v1.0
- [UltraCore-RFT](https://github.com/RFT-SIRM/UltraCore-RFT) — seL4 CDT validation & formal methods track
- [agave-rift-scheduler](https://github.com/RFT-SIRM/agave-rift-scheduler) — Conflict-aware scheduler research
- [aave-v4-hub-model-review](https://github.com/RFT-SIRM/aave-v4-hub-model-review) — DeFi invariant model review
- [agave-abiv2-memory-contexts](https://github.com/RFT-SIRM/agave-abiv2-memory-contexts) — ABIv2 memory isolation research

---

## Verification Stack

```
L1  Static Analysis    → Clippy, Miri, cargo-audit
L2  Engineering Tests  → 15+ tests/component, differential hash
L3  Stateful Fuzzing   → libFuzzer, 4.29B+ executions
L3b Kernel Validation   → seL4 CDT, 1B+ ops, 123/123 tests
L3c DeFi Model Fuzz    → Aave V4 Hub, 184K ops
L4  Formal Methods     → TLA+ & Coq (planned)
```

---

## SIRM Invariants

| ID | Name | Status |
|----|------|--------|
| I1 | Supply Conservation | ✅ Validated |
| I2 | Mint/Burn Accounting | ✅ Validated |
| I3 | Dust Bound | ✅ Validated |
| I4 | Debt Limit | ✅ Validated |

---

## License

Apache 2.0

---

*RFT-SIRM Laboratory — Est. 2026*
