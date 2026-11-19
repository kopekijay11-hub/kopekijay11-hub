# Joshua Normandin — Backend and Systems Engineer

Self-taught software developer in Ottawa, Canada. I build Java and Python systems with strong testing and operational discipline — and the tooling that proves they work. I am seeking backend, platform, or developer-tooling roles in Ottawa or remotely.

## Projects

| Project | What it is | Evidence | Status |
|---|---|---|---|
| [Feedline](https://github.com/kopekijay11-hub/feedline) | Scheduled feed-ingestion service — Java 21, Spring Boot 3, PostgreSQL 16, Flyway migrations, Maven build. Rigor flagship: milestones graded from origin, decisions recorded in the repo ([DECISIONS.md](https://github.com/kopekijay11-hub/feedline/blob/main/DECISIONS.md)). | Runnable from the repo (Docker Compose + Maven); milestone reports, design decisions (DECISIONS.md), and handoff notes included | M1 + M2a merged to main, CI green [![CI](https://github.com/kopekijay11-hub/feedline/actions/workflows/ci.yml/badge.svg)](https://github.com/kopekijay11-hub/feedline/actions/workflows/ci.yml) |
| [Scanline](https://github.com/kopekijay11-hub/Scanline) | Deterministic market-condition event scanner — Python, stdlib only. Sweeps price state across a symbol book and emits validated as-of event streams (level proximity first) as an offline research feed; the as-of validator is the deliverable, and parameter files are frozen and hash-bound before any scan period they govern | Event schema, five-rule as-of validator, band-crossing predicate, and synthetic-fixture proof suites in the repo; work orders filed in-repo and every result graded from origin | Module 1 (level proximity) built and verified from origin — 35/35 tests; parameter freeze and first real-data scan next |
| [OrbitAlgo](https://github.com/kopekijay11-hub/OrbitAlgo) | Autonomous algorithmic trading system in Python — multi-strategy engine, per-symbol configuration, layered risk breakers, and a pre-registered validation funnel (SELECT → VALIDATE → sealed HOLDOUT) | Architecture, validation methodology, and audit summaries in the repo; the private production system it documents measures 40,000+ lines and 2,300+ tests, verified in the private environment | Runs autonomously on a MetaTrader 5 demo account; production codebase private by design |
| [Agent Evaluation Harness](https://github.com/kopekijay11-hub/agent-eval-harness-showcase) | Deterministic test bench for AI coding agents — frozen task batteries, tool-call grading, a failure taxonomy, and regression detection across prompt and model changes | Trace format, JSON Schema, a worked example trace, and measured results in the repo | Family gates F1 and F2 passed (Stage A: 71/120 trials); parked pending the next phase |

## How I work

- Test-first, verified against the record: if a result can't be reproduced from the artifacts, it doesn't count.
- Pre-registered criteria for experiments — bars are set before the run, and a miss is reported as a miss.
- Everything runs on free or local tooling wherever it can.

## Toolkit

Python · Java 21 · Spring Boot · FastAPI · PostgreSQL · SQLite · pytest · JUnit · Maven · Git · Linux · MetaTrader 5

## Contact

Email: kopekijay11@gmail.com · Ottawa, Canada

Best reached by email or through GitHub. Open to backend, platform, and developer-tooling roles — remote from Ottawa, or Ottawa-based.
