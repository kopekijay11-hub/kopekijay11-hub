# Joshua Normandin — Backend and Systems Engineer

Self-taught software developer in Ottawa, Canada. I build Java and Python systems with strong testing and operational discipline — and the tooling that proves they work. I am seeking backend, platform, or developer-tooling roles in Ottawa or remotely.

## Projects

| Project | What it is | Evidence | Status |
|---|---|---|---|
| [Feedline](https://github.com/kopekijay11-hub/feedline) | Scheduled feed-ingestion service — Java 21, Spring Boot 3, PostgreSQL 16, Flyway migrations, Maven build. Rigor flagship: milestones graded from origin, decisions recorded in the repo ([DECISIONS.md](https://github.com/kopekijay11-hub/feedline/blob/main/DECISIONS.md)). | Runnable from the repo (Docker Compose + Maven); milestone reports, design decisions (DECISIONS.md), an operations dashboard, and handoff notes included | **Complete** — M1–M3, independent audit 98/100 with every finding closed, 174 tests, SpotBugs clean, final README with a recorded fresh-clone quickstart; running live |
| [Scanline](https://github.com/kopekijay11-hub/scanline) | Deterministic market-condition event scanner — Python, stdlib only. Sweeps price state across a symbol book and emits validated as-of event streams as an offline research feed; the as-of validator is the deliverable, and parameter files are frozen and hash-bound before any scan period they govern | Event schema, five-rule as-of validator, and synthetic-fixture proof suites in the repo; every scan published with a hash-bound ledger; work orders filed in-repo and every result graded from origin | **Build phase complete** — two modules, each frozen, pre-registered, and confirmed on held-out data; three published scans (latest: 4,624 events); 388 tests; remaining modules blocked on data the corpus does not have |
| [OrbitAlgo](https://github.com/kopekijay11-hub/OrbitAlgo) | Autonomous algorithmic trading system in Python — multi-strategy engine, per-symbol configuration, layered risk breakers, and a pre-registered validation funnel (SELECT → VALIDATE → sealed HOLDOUT) | Architecture, validation methodology, and audit summaries in the repo; the private production system it documents measures 132,035 lines of Python (91,877 production, 40,158 tests) and 2,400+ tests, verified in the private environment | Runs autonomously on a MetaTrader 5 demo account; full-system re-audit and pre-registered reassessment completed November 2026; production codebase private by design |
| [Agent Evaluation Harness](https://github.com/kopekijay11-hub/agent-eval-harness-showcase) | Deterministic test bench for AI coding agents — frozen task batteries, tool-call grading, a failure taxonomy, and regression detection across prompt and model changes | Trace format, JSON Schema, a worked example trace, and measured results in the repo | Stage A complete — 103/252 trials across four frozen task families; Stage B calibration under way |

## How I work

- Test-first, verified against the record: if a result can't be reproduced from the artifacts, it doesn't count.
- Pre-registered criteria for experiments — bars are set before the run, and a miss is reported as a miss.
- Everything runs on free or local tooling wherever it can.

## Toolkit

Python · Java 21 · Spring Boot · FastAPI · PostgreSQL · SQLite · Kafka · Docker · pytest · JUnit · Maven · Git · Linux · MetaTrader 5

## Contact

Email: kopekijay11@gmail.com · Ottawa, Canada
Hugging Face: [huggingface.co/kopekijay11](https://huggingface.co/kopekijay11) · X: [@kopekijay11](https://x.com/kopekijay11)

Best reached by email or through GitHub. Open to backend, platform, and developer-tooling roles — remote from Ottawa, or Ottawa-based.
