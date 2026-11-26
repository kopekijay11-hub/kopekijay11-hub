# Joshua Normandin — Backend and Systems Engineer

Self-taught software developer in Ottawa, Canada. I build Java and Python systems with strong testing and operational discipline — and the tooling that proves they work. I am seeking backend, platform, or developer-tooling roles in Ottawa or remotely.

## Projects

| Project | What it is | Evidence | Status |
|---|---|---|---|
| [Feedline](https://github.com/kopekijay11-hub/feedline) | Scheduled feed-ingestion service — Java 21, Spring Boot 3, PostgreSQL 16, Flyway migrations, Maven build. Rigor flagship: milestones graded from origin, decisions recorded in the repo ([DECISIONS.md](https://github.com/kopekijay11-hub/feedline/blob/main/DECISIONS.md)). | Runnable from the repo (Docker Compose + Maven); milestone reports, design decisions (DECISIONS.md), an operations dashboard, and handoff notes included | **Complete and running live** — M1–M3, independent audit 98/100 with every finding closed, 248 tests, SpotBugs clean; 40 sources polling live with category RSS feeds served, plus a reader dashboard with a category explorer, per-feed subscribe popovers, and a top-stories view |
| [Scanline](https://github.com/kopekijay11-hub/scanline) | Deterministic market-condition event scanner — Python, stdlib only. Sweeps price state across a symbol book and emits validated as-of event streams as an offline research feed; the as-of validator is the deliverable, and parameter files are frozen and hash-bound before any scan period they govern | Event schema, five-rule as-of validator, and synthetic-fixture proof suites in the repo; every scan published with a hash-bound ledger; work orders filed in-repo and every result graded from origin | **Build phase complete** — two modules, each frozen, pre-registered, and confirmed on held-out data; three published scans (latest: 4,624 events); 388 tests; remaining modules blocked on data the corpus does not have |
| [OrbitAlgo](https://github.com/kopekijay11-hub/OrbitAlgo) | Autonomous algorithmic trading system in Python — multi-strategy engine, per-symbol configuration, layered risk breakers, and a pre-registered validation funnel (SELECT → VALIDATE → sealed HOLDOUT) | Architecture, validation methodology, and audit summaries in the repo; the private production system it documents measures 132,035 lines of Python (91,877 production, 40,158 tests) and 2,400+ tests, verified in the private environment | Runs autonomously on a MetaTrader 5 demo account; full-system re-audit completed November 2026; a tamper-evident decision recorder and a pre-registered holdout-reservation ledger are built and verified in the private system; production codebase private by design |
| [Agent Evaluation Harness](https://github.com/kopekijay11-hub/agent-eval-harness-showcase) | Deterministic test bench for AI coding agents — frozen task batteries, tool-call grading, a failure taxonomy, and regression detection across prompt and model changes | Trace format, JSON Schema, a worked example trace, and measured results in the repo | Stages A–D complete — calibration campaign closed and frozen; a full commissioning campaign is pre-registered with a fixed compute envelope |
| [Parapix](https://github.com/kopekijay11-hub/parapix) | Statistical validation toolkit for strategy research — Python. One-sided sign-flip permutation tests, circular block bootstrap, Bonferroni evaluation, and a deflated Sharpe ratio, behind a hash-bound self-validation runner: validations execute only from committed code on a clean tree, bound to the exact commit that produced them | Modules verified against published references (Politis & White block-length selection; Bailey & López de Prado deflated Sharpe); 78 tests | v0.1.0 released — public under MIT; v0.2 in development with continuous integration on every push (the suite runs with and without the arch reference library); validation bars and bound artifacts in the repo |

## How I work

- Test-first, verified against the record: if a result can't be reproduced from the artifacts, it doesn't count.
- Pre-registered criteria for experiments — bars are set before the run, and a miss is reported as a miss.
- Everything runs on free or local tooling wherever it can.

## Toolkit

Python · NumPy · Java 21 · Spring Boot · FastAPI · PostgreSQL · SQLite · Kafka · Docker · pytest · JUnit · Maven · Git · Linux · MetaTrader 5

## Contact

Email: kopekijay11@gmail.com · Ottawa, Canada
Hugging Face: [huggingface.co/kopekijay11](https://huggingface.co/kopekijay11) · X: [@kopekijay11](https://x.com/kopekijay11)

Best reached by email or through GitHub. Open to backend, platform, and developer-tooling roles — remote from Ottawa, or Ottawa-based.
