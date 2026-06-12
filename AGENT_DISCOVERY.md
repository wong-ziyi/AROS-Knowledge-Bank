---
title: AROS Knowledge Bank — Agent Discovery Manifest
version: "1.0.0"
updated: "2026-06-12"
purpose: Machine-readable index for AI coding agent pre-flight injection
---

# AROS Knowledge Bank — Agent Discovery Manifest

> **FOR AI AGENTS**: This file is the primary entry point for automated knowledge retrieval.
> Parse the structured tables below to locate relevant source code and literature.

## Discovery Protocol

When an AI agent encounters a task involving any of the following domains, it MUST:

1. **Search this Knowledge Bank FIRST** before web search or general knowledge.
2. **Read the parsed Markdown** in `Literature/03_Parsed_Markdown/<arXiv_ID>.md` for the relevant paper section.
3. **Inspect the project source code** in `Projects/<project_name>/` for reference implementations.
4. **Cite sources** in commit messages or walkthroughs when solutions are derived from this bank.

### Domain → Resource Mapping

| Domain | Primary Papers | Reference Projects |
|---|---|---|
| Agentic Memory (brain.db, world_facts, experiences) | 2406.18312, 2512.10696, 2512.12818, 2504.19413, 2605.29640 | mem0, memU, hindsight, ReMe, OpenViking |
| Skill Evolution (GEPA, SkillOpt, hierarchical skills) | 2604.04804, 2605.23904, 2605.27366 | SkillX, SkillOpt |
| LLM-OS Architecture | 2406.18312, 2503.08102, memgpt_paper | letta, Second-Me |
| Self-Distillation & Personalization | 2503.08102 | Second-Me |
| Meta-Programming & Knowledge Systems | — | meta-meme, memos, text2meme |

### Paper → AROS Milestone Mapping

| Paper (arXiv ID) | AROS Self-Evolution Track | Milestones |
|---|---|---|
| 2604.04804 (SkillX) | Track H: Hierarchical Skill Architecture | MS-H1, MS-H2, MS-H3 |
| 2605.23904 (SkillOpt) | Track J: Bounded Optimization Upgrades | MS-J1, MS-J2 |
| 2605.27366 (MUSE-Autoskill) | Tracks I, K, L: Skill Memory, Testing, Transfer | MS-I1, MS-I2, MS-K1, MS-K2, MS-L1 |

### Project Index (Submodules)

| Directory | Remote URL | Primary Language | Stars (approx) |
|---|---|---|---|
| `Projects/memU` | https://github.com/NevaMind-AI/memU | Python | — |
| `Projects/hindsight` | https://github.com/vectorize-io/hindsight | Rust/Python | ~500 |
| `Projects/mem0` | https://github.com/mem0ai/mem0 | Python | ~25K |
| `Projects/letta` | https://github.com/letta-ai/letta | Python | ~15K |
| `Projects/ReMe` | https://github.com/agentscope-ai/ReMe | Python | ~200 |
| `Projects/memos` | https://github.com/usememos/memos | Go | ~35K |
| `Projects/OpenViking` | https://github.com/volcengine/OpenViking | Python | ~500 |
| `Projects/Second-Me` | https://github.com/mindverse/Second-Me | Python | ~5K |
| `Projects/meta-meme` | https://github.com/meta-introspector/meta-meme | Mixed | — |
| `Projects/text2meme` | https://github.com/abhishtagatya/text2meme | Python | ~200 |
| `Projects/SkillX` | https://github.com/zjunlp/SkillX | Python | ~300 |
| `Projects/SkillOpt` | https://github.com/microsoft/SkillOpt | Python | ~500 |

### Literature File Paths

| arXiv ID | PDF | Parsed Markdown | JSON Metadata |
|---|---|---|---|
| 2605.29640 | `Literature/02_Raw_PDFs/2605.29640.pdf` | `Literature/03_Parsed_Markdown/2605.29640.md` | `Literature/03_Parsed_Markdown/2605.29640.json` |
| 2406.18312 | `Literature/02_Raw_PDFs/2406.18312.pdf` | `Literature/03_Parsed_Markdown/2406.18312.md` | `Literature/03_Parsed_Markdown/2406.18312.json` |
| 2503.08102 | `Literature/02_Raw_PDFs/2503.08102.pdf` | `Literature/03_Parsed_Markdown/2503.08102.md` | `Literature/03_Parsed_Markdown/2503.08102.json` |
| 2512.10696 | `Literature/02_Raw_PDFs/2512.10696.pdf` | `Literature/03_Parsed_Markdown/2512.10696.md` | `Literature/03_Parsed_Markdown/2512.10696.json` |
| 2512.12818 | `Literature/02_Raw_PDFs/2512.12818.pdf` | `Literature/03_Parsed_Markdown/2512.12818.md` | `Literature/03_Parsed_Markdown/2512.12818.json` |
| 2504.19413 | `Literature/02_Raw_PDFs/2504.19413.pdf` | `Literature/03_Parsed_Markdown/2504.19413.md` | `Literature/03_Parsed_Markdown/2504.19413.json` |
| 2604.04804 | `Literature/02_Raw_PDFs/2604.04804v2.pdf` | `Literature/03_Parsed_Markdown/2604.04804v2.md` | `Literature/03_Parsed_Markdown/2604.04804v2.json` |
| 2605.23904 | `Literature/02_Raw_PDFs/2605.23904v2.pdf` | `Literature/03_Parsed_Markdown/2605.23904v2.md` | `Literature/03_Parsed_Markdown/2605.23904v2.json` |
| 2605.27366 | `Literature/02_Raw_PDFs/2605.27366v1.pdf` | `Literature/03_Parsed_Markdown/2605.27366v1.md` | `Literature/03_Parsed_Markdown/2605.27366v1.json` |
| memgpt | `Literature/02_Raw_PDFs/memgpt_paper.pdf` | `Literature/03_Parsed_Markdown/memgpt_paper.md` | `Literature/03_Parsed_Markdown/memgpt_paper.json` |
