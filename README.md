# AROS Knowledge Bank

> **Ecosystem direction · 5 October 2026:** [Current strategy and role](docs/AROS_STRATEGY.md). AROS is commercially prelaunch; this repository’s source and release records establish only their stated technical scope. The first business gate is repeated external value and sustainable paid delivery.

> **Foundational Literature & Project Codebases for the [Antigravity Research OS (AROS)](https://github.com/LabOnoM/AROS)**

This repository is the permanent knowledge bank that houses the academic papers and open-source project codebases that directly inspired the AROS architecture. It serves as the **primary reference source** for AI coding agents when debugging, troubleshooting, or implementing features related to agentic memory, skill evolution, and LLM-OS design patterns.

---

## 📚 Literature

All papers are stored in `Literature/` with the following structure:

| # | arXiv ID | Title | Year | Relevance to AROS |
|---|---|---|---|---|
| 1 | [2605.29640](Literature/03_Parsed_Markdown/2605.29640.md) | **VikingMem** — Viking Memory for LLM Agents | 2025 | Memory architecture patterns |
| 2 | [2406.18312](Literature/03_Parsed_Markdown/2406.18312.md) | **AI-Native Memory** — Architecture for LLM Agents | 2024 | Core memory system design |
| 3 | [2503.08102](Literature/03_Parsed_Markdown/2503.08102.md) | **Second-Me** — AI Clone via Self-Distillation | 2025 | Personalization & distillation |
| 4 | [2512.10696](Literature/03_Parsed_Markdown/2512.10696.md) | **ReMe** — Dynamic Memory for LLM Agents | 2025 | Dynamic memory management |
| 5 | [2512.12818](Literature/03_Parsed_Markdown/2512.12818.md) | **Hindsight** — Proactive Memory for LLM Agents | 2025 | Proactive hindsight fusion |
| 6 | [2504.19413](Literature/03_Parsed_Markdown/2504.19413.md) | **Mem0** — Memory Layer for LLM Applications | 2025 | Memory layer abstraction |
| 7 | [2604.04804](Literature/03_Parsed_Markdown/2604.04804v2.md) | **SkillX** — Automatically Constructing Skill Knowledge Bases | 2026 | Hierarchical skill architecture (Track H) |
| 8 | [2605.23904](Literature/03_Parsed_Markdown/2605.23904v2.md) | **SkillOpt** — Executive Strategy for Self-Evolving Agent Skills | 2026 | Bounded text-space optimization (Track J) |
| 9 | [2605.27366](Literature/03_Parsed_Markdown/2605.27366v1.md) | **MUSE-Autoskill** — Self-Evolving Agents via Skill Lifecycle | 2026 | Full skill lifecycle management (Tracks I, K, L) |
| 10 | — | **MemGPT** — Towards LLMs as Operating Systems | 2023 | Original LLM-OS concept |

### Literature Directory Layout

```
Literature/
├── 01_Target_DOIs.txt          # Master DOI list
├── 02_Raw_PDFs/                # Original PDF downloads
├── 03_Parsed_Markdown/         # LLM-readable Markdown conversions (with images)
├── 04_Parsed_JSON/             # Structured JSON metadata
└── 05_Metadata/                # Bibliographic metadata
```

---

## 🔧 Projects (Git Submodules)

All project codebases are tracked as **Git Submodules** — lightweight pointers to the original repositories. To initialize them:

```bash
git submodule update --init --recursive
# Or clone with submodules:
git clone --recurse-submodules https://github.com/wong-ziyi/AROS-Knowledge-Bank.git
```

| Project | Repository | Category | AROS Relevance |
|---|---|---|---|
| **memU** | [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) | Memory | Unified memory framework |
| **hindsight** | [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) | Memory | Proactive hindsight fusion architecture |
| **mem0** | [mem0ai/mem0](https://github.com/mem0ai/mem0) | Memory | Memory layer for LLM applications |
| **letta** | [letta-ai/letta](https://github.com/letta-ai/letta) | LLM-OS | MemGPT successor — stateful LLM agents |
| **ReMe** | [agentscope-ai/ReMe](https://github.com/agentscope-ai/ReMe) | Memory | Dynamic memory for multi-agent systems |
| **memos** | [usememos/memos](https://github.com/usememos/memos) | Notes | Privacy-first memo/knowledge system |
| **OpenViking** | [volcengine/OpenViking](https://github.com/volcengine/OpenViking) | Memory | Viking memory system implementation |
| **Second-Me** | [mindverse/Second-Me](https://github.com/mindverse/Second-Me) | Personalization | AI clone via self-distillation |
| **meta-meme** | [meta-introspector/meta-meme](https://github.com/meta-introspector/meta-meme) | Meta | Meta-programming for meme evolution |
| **text2meme** | [abhishtagatya/text2meme](https://github.com/abhishtagatya/text2meme) | Utility | Text-to-meme generation |
| **SkillX** | [zjunlp/SkillX](https://github.com/zjunlp/SkillX) | Skills | Hierarchical skill knowledge base construction |
| **SkillOpt** | [microsoft/SkillOpt](https://github.com/microsoft/SkillOpt) | Skills | Text-space skill optimization |

---

## 🤖 For AI Agents

See [`AGENT_DISCOVERY.md`](AGENT_DISCOVERY.md) for the machine-readable discovery manifest.

**Protocol**: When debugging or implementing features related to agentic memory, skill evolution, or LLM-OS architecture in AROS, search this Knowledge Bank **FIRST** before web search.

---

## 📖 Documentation Site (Optional)

This repository includes an optional [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) configuration for building a searchable static site:

```bash
pip install mkdocs-material
mkdocs serve        # Local preview at http://localhost:8000
mkdocs gh-deploy    # Deploy to GitHub Pages
```

---

## License

Literature PDFs are subject to their respective publisher licenses. Project submodules carry their own licenses (see individual repositories). This index and documentation are MIT-licensed.
