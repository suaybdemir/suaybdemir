## Suayb Demir

> **Backend systems for when things go wrong.**  
> Architectural decisions, enforced at code level.

[![Portfolio](https://img.shields.io/badge/suaybdemir.com-000?style=flat)](https://suaybdemir.com)
[![Resume](https://img.shields.io/badge/Resume-000?style=flat)](https://suaybdemir.com/assets/resume.pdf)

---

### What I work on

_I don't optimize for happy paths._

- Event-driven backend systems with explicit failure modeling
- Architectural decisions mapped directly to code and failure modes
- Backpressure, rate limiting, circuit breakers, idempotency
- Observability treated as a system constraint, not a tool choice

---

## 🧩 CloudScale Event Platform

High-throughput event ingestion platform designed around failure modes, backpressure, and operational trade-offs.

> "What breaks first, and how do we know?"

What makes it different:
- Architectural decisions (D00X) documented and cross-referenced with code
- Failure scenarios (F00X) defined with triggers, blast radius, and escape hatches
- Every critical code path annotated with decision links and failure breakpoints
- Known gaps explicitly documented, not hidden

**Navigation**

| Document | Purpose |
|----------|---------|
| [Architecture](https://github.com/suaybdemir/CloudScale-Event-Platform/blob/main/docs/architecture.md) | System shape & constraints |
| [Decision Log](https://github.com/suaybdemir/CloudScale-Event-Platform/blob/main/docs/decision-log.md) | Why choices were made |
| [Failure Scenarios](https://github.com/suaybdemir/CloudScale-Event-Platform/blob/main/docs/failure-scenarios.md) | How the system breaks |

---

### Principles

- Making trade-offs explicit and reviewable
- Designing systems that fail loudly, not silently
- Leaving artifacts that outlive the original authors

---

### Research / Learning

**[MiDeSeC-YOLOv11](https://github.com/suaybdemir/MiDeSeC-YOLOv11)** — Mitosis detection in histopathological images. Recall-optimized experiment on MiDeSeC dataset (internal split only).

---

> This profile is not about demos.  
> It's about systems that survive bad days.
