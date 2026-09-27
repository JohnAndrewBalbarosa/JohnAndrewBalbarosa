### Hi, I'm Balby.

I build and evaluate LLM systems: evaluation pipelines, agent orchestration, and the automation around them. I study computer science at FEU Institute of Technology, intern at [Symph](https://github.com/symphco), and lead Campus Labs for PyTorch Philippines at FEU Tech.

I came to machine learning through mathematics, so I care about first principles and about claims that can be reproduced.

#### Now · September 2026

**Featured: [codex-observability-hub](https://github.com/JohnAndrewBalbarosa/codex-observability-hub)**, a local-first observability stack for AI coding agents on Windows. It captures lifecycle events, correlates prompts with tool activity and code versions, and spools to SQLite when PostgreSQL is offline. Tested with Codex only.

Also this month: interning at Symph.

#### Featured log

One project per month. The month is the latest push or merge, and the evidence column quotes that project's own README or pull request.

| Month | Project | What it does | Evidence |
|---|---|---|---|
| 2026-09 | [codex-observability-hub](https://github.com/JohnAndrewBalbarosa/codex-observability-hub) | Structured logging and tracing for AI coding sessions | Unit tests and a health check ship with the repo. No quantitative results published yet. |
| 2026-08 | [recruitment-pipeline-automation](https://github.com/JohnAndrewBalbarosa/recruitment-pipeline-automation) | Airtable recruitment pipeline with repeat-safe n8n job imports, validation, and deduplication | Repository validation script and a read-only Airtable audit. No quantitative results published yet. |
| 2026-07 | [rdtii-autoextract](https://github.com/JohnAndrewBalbarosa/rdtii-autoextract) | Model-agnostic pipeline that drafts citation-backed findings for the UN ESCAP RDTII digital-trade review | Deterministic cleaning cut raw HTML from 77,125 to 9,743 tokens on the `inspect_au` fixture (87.4%). Final verification stays a human-review step. |
| 2026-06 | [pytorch-fit-system #111](https://github.com/PyTorch-FEU-Tech-Chapter/pytorch-fit-system/pull/111) | Offline-reproducible benchmark of agent tool-calling against a crawler pipeline, by token cost | Merged. Naive tool-calling grows O(N²) in tokens; the pipeline grows O(N) plus a bounded per-layout cost. |

#### Research and evaluation

| Project | Question | Result |
|---|---|---|
| [NeoTerritory](https://github.com/JohnAndrewBalbarosa/NeoTerritory) | Can deterministic structural analysis give students source-anchored feedback on C++ design patterns? | 50 participants, 150 runs: compile pass rate 90.0% (135/150), static-analysis pass rate 88.0% (132/150), unit-test pass rate 84.2% (235/279). |
| [Prompt-Engineering-for-Research-Ollama-Based](https://github.com/JohnAndrewBalbarosa/Prompt-Engineering-for-Research-Ollama-Based) | Does chain-of-thought prompting help local models on GSM8K? | Mean accuracy rose from 50% to 67%. qwen2.5:7b went from 60% to 95%, while llama2:13b-chat fell from 20% to 10%, so the gain is not universal. |

#### In progress, not yet measured

- [MCP](https://github.com/JohnAndrewBalbarosa/MCP): DAG-based multi-agent orchestration over Model Context Protocol, with swappable LLM backends.
- [harness-signal](https://github.com/JohnAndrewBalbarosa/harness-signal): an XML signal contract for driving agent CLIs headlessly, one turn at a time.
- [Andrew-mini-compiler](https://github.com/JohnAndrewBalbarosa/Andrew-mini-compiler): lexical analysis, CYK parsing, and semantic type checking in C++.

#### How to read the numbers

Every figure on this page is copied from the linked README or pull request, which holds the dataset, sample size, metric, and reproduction steps. A project with no measured result says so.

#### Community

- Campus Labs Lead, PyTorch Philippines at FEU Tech, where I am helping start the campus community.
- Competitive programming: Algolympics, ICPC, Sikaptala Python Competition.
- Second Place, MATH COUNT 2024 (MTAP-TL), with FEU Institute of Technology.

#### Links

- Organization: [PyTorch FEU Tech Chapter](https://github.com/PyTorch-FEU-Tech-Chapter)
- Work: [Symph](https://github.com/symphco)
