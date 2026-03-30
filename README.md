## Suayb Demir

> **Backend systems for when things go wrong.**
> Architectural decisions, enforced at code level.

[![Portfolio](https://img.shields.io/badge/suaybdemir.com-000?style=flat&logo=globe&logoColor=white)](https://suaybdemir.com)
[![Resume](https://img.shields.io/badge/Resume-4A4A4A?style=flat&logo=adobeacrobatreader&logoColor=white)](https://suaybdemir.com/assets/resume.pdf)

---

### What I work on

_I don't optimize for happy paths._

- Event-driven backend systems with explicit failure modeling
- Architectural decisions mapped directly to code and failure modes
- Backpressure, rate limiting, circuit breakers, idempotency
- Observability treated as a system constraint, not a tool choice

### Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=suaybdemir&show_icons=false&hide_border=true&theme=github_dark">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=suaybdemir&show_icons=false&hide_border=true&theme=default">
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=suaybdemir&show_icons=false&hide_border=true">
</picture>

---

## CloudScale Event Platform

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

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/suaybdemir/suaybdemir/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/suaybdemir/suaybdemir/output/github-contribution-grid-snake.svg">
  <img alt="contribution snake" src="https://raw.githubusercontent.com/suaybdemir/suaybdemir/output/github-contribution-grid-snake.svg">
</picture>

> This profile is not about demos.
> It's about systems that survive bad days.
