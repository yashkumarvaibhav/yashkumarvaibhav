<h1 align="center">Yash Kumar Vaibhav</h1>

<p align="center">
  Software Engineer · Backend & Distributed Systems · Applied ML and LLM Systems
</p>

<p align="center">
  <a href="https://yashkumarvaibhav.me"><img src="https://img.shields.io/badge/Portfolio-yashkumarvaibhav.me-277A75?style=flat-square" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/yashkumarvaibhav/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://codeforces.com/profile/yashkumarvaibhav"><img src="https://img.shields.io/badge/Codeforces-Expert-1F8ACB?style=flat-square&logo=codeforces&logoColor=white" alt="Codeforces Expert"/></a>
  <a href="mailto:yashkumarvaibhav.official@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

I am a software engineer focused on backend and distributed systems, with applied machine-learning
and LLM work where outputs are designed to be checked. I am completing an M.Tech in Computer Science
and Engineering at IIIT-Delhi (CGPA 9.52) after a B.E. in CSE from Thapar Institute.

Before the M.Tech, I spent 2.25 years at SivaTech Solutions: a six-month internship followed by 1.75
years on a full-time contract. I worked on the C++ backend of a proprietary algorithmic-trading
platform, including latency-critical order execution, multithreaded components, market-data feeds,
and trading logic.

## Featured engineering work

### [Sentinel](https://github.com/yashkumarvaibhav/sentinel) — observability and verified remediation

Python 3.12 · FastAPI · Kafka/Redpanda · ClickHouse · PostgreSQL · OpenTelemetry · Kubernetes

Decomposes traffic surges into baseline, event-explained, and unexplained residuals, then requires a
deterministic verifier before a reversible action can run. The lab uses real telemetry with injected
faults and attacks, labels simulated evidence explicitly, and is held to 1,000+ Python tests plus a
four-job CI pipeline. [Live command center](https://sentinel.yashkumarvaibhav.me)

### [Job Pilot](https://github.com/yashkumarvaibhav/job-pilot) — multi-tenant job-search CRM

TypeScript · Next.js · React · SQLite · Drizzle ORM · Gmail API · OAuth 2.0

A deterministic CRM and outreach engine for companies, contacts, applications, referrals, tasks,
and email sequences. The Gmail path separates inbox freshness from thread-level send safety, and
every third-party sequence message needs its own approval. The project includes 31 schema migrations,
workspace-scoped data boundaries, replay-safe TOTP, and verified backup/restore tooling.
[Live early access](https://jobpilot.yashkumarvaibhav.me)

### [ELECTRA for Human Gut Microbiomes](https://github.com/yashkumarvaibhav/DL-HumanGutMicrobiome) — cross-study ML evaluation

Python · PyTorch · Hugging Face Transformers · scikit-learn · Self-supervised learning

Trained ELECTRA from scratch over 16,721 microbiome samples across 129 studies. The best
study-overlapping split reached 0.8518 AUROC; a five-study leave-one-study-out evaluation fell to a
0.6312 macro mean, exposing the batch effects hidden by the stronger headline number.

### GWiz — human-in-the-loop LLM assistant for Google Workspace

Python · FastAPI · LangGraph · OAuth 2.0 · React · TypeScript

On a shared five-contributor project, I owned the backend around checkpointed approve/edit/cancel
flows, ten Workspace APIs, and a multi-provider LLM layer. The application uses the open-source,
pre-1.0 Google Workspace CLI (`gws`) with a direct-REST fallback only when the CLI itself fails, and
the repository is held to 750+ pytest tests. [Live application](https://gwiz.yashkumarvaibhav.me)

### [TradeVault](https://github.com/yashkumarvaibhav/TradeVault) — deterministic trading-risk workbench

TypeScript · Next.js · PostgreSQL · Monte Carlo · Kelly criterion · Web Workers

A trading journal whose pure domain core bootstraps deterministic Monte Carlo paths from realized
R-multiples and computes Kelly sizing two ways. Every result carries “historical scenario, not a
forecast,” enforces a 30-trade minimum, and keeps INR and USD accounting separate.
[Live application](https://tradevault.yashkumarvaibhav.me)

### [CoExist Alert](https://github.com/yashkumarvaibhav/CoExist-Alert) — edge early warning for human–wildlife conflict

TypeScript · Next.js · SQLite · Cisco Webex · Vitest · Playwright

Team GitBoosters' Code with Cisco 2026 finalist project. The field sensor network is simulated and
labelled; Webex dispatch is live when configured. The platform combines signal confirmation, alert
escalation, sensor-health monitoring, and responder workflows with 280 unit tests and 18 Playwright
specifications. [Live demonstration](https://coexist.yashkumarvaibhav.me)

## Technical focus

| Area | Technologies and concepts |
| --- | --- |
| Backend and distributed systems | Python, C++, TypeScript, FastAPI, Node.js, REST APIs, Kafka, stream processing, concurrency |
| Data and infrastructure | PostgreSQL, SQLite, ClickHouse, Docker, Kubernetes, OpenTelemetry, Linux |
| ML and LLM systems | PyTorch, Hugging Face Transformers, scikit-learn, LangGraph, human-in-the-loop workflows, evaluation and guardrails |
| Verification | pytest, Vitest, Playwright, property-based testing, strict typing, CI, deterministic replay |

## How I build

For my independently directed systems, I write the specifications and decision logs, choose the
architecture and trade-offs, and use coding agents through a spec-driven workflow with test gates.
The product decisions are mine, and I prepare to explain the critical components from first
principles. Team projects such as GWiz and CoExist Alert are identified as team work and credited as
such.

## Selected credentials

- Codeforces Expert — maximum rating 1728
- Code with Cisco 2026 — finalist (top 75 of approximately 30,000) and Gold Flag Challenge winner
- Amazon ML Summer School 2026 — selected among the top 3,000 of 134,421 registrants
- 500+ algorithmic problems solved across LeetCode and Code360

I am open to software engineering, backend, distributed-systems, and machine-learning engineering
opportunities.
