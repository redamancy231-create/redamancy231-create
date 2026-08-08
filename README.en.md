> [简体中文](README.md) | English | [正體中文](README.zh-Hant.md)

### Hi, I'm redamancy231 👋

**I build reproducible Human-AI collaboration frameworks, quantitative engineering tools, and multi-model LLM review pipelines.**

All 11 repos are battle-tested through cross-model independent review.

All repos are trilingual (zh-CN / zh-Hant / EN). Each language is a standalone file, cross-linked via the language bar above.

---

## 🚀 Projects

### Methodology

| Project | What it is | Release | Status |
|------|------|:--:|:--:|
| [**AI 协作框架**](https://github.com/redamancy231-create/ai-collaboration-framework) | Full-lifecycle Human-AI collaboration framework — 3 controlled experiments + 50+ rounds of cross-model review | ![Release](https://img.shields.io/github/v/release/redamancy231-create/ai-collaboration-framework) | active |
| [**Methodology Handbook**](https://github.com/redamancy231-create/methodology-handbook) | 50 battle-tested lessons at a glance — the "error logbook" companion | ![Release](https://img.shields.io/github/v/release/redamancy231-create/methodology-handbook) | published |
| [**Prompt-TDD Methodology**](https://github.com/redamancy231-create/prompt-tdd-methodology) | Prompt experiment casebook — includes 2 real experiment results (negative results published) | ![Release](https://img.shields.io/github/v/release/redamancy231-create/prompt-tdd-methodology) | published |
| [**M&A Case Study Pipeline**](https://github.com/redamancy231-create/ma-case-study-pipeline) | 8-stage multi-model academic pipeline — double-blind cross-review + open/closed-book experiment | ![Release](https://img.shields.io/github/v/release/redamancy231-create/ma-case-study-pipeline) | demo |
| [**Methodology Extraction Methodology**](https://github.com/redamancy231-create/methodology-extraction-methodology) | Meta-level methodology extraction experiment — systematic extraction from 22 projects | ![Release](https://img.shields.io/github/v/release/redamancy231-create/methodology-extraction-methodology) | maintenance |

### Review & Quality Assurance

| Project | What it is | Release | Status |
|------|------|:--:|:--:|
| [**Independent Review Toolkit**](https://github.com/redamancy231-create/independent-review-toolkit) | Multi-model independent review SOP · Prompt templates · Adversarial challenge framework | ![Release](https://img.shields.io/github/v/release/redamancy231-create/independent-review-toolkit) | published |
| [**Negative Results Registry**](https://github.com/redamancy231-create/negative-results-registry) | AI Collaboration Negative Results Registry — 23 entries × 10 domains, a structured database of "AI experiments that failed" | ![Release](https://img.shields.io/github/v/release/redamancy231-create/negative-results-registry) | active |

### Dev Tools

| Project | What it is | Release | Status |
|------|------|:--:|:--:|
| [**DOCX Pipeline**](https://github.com/redamancy231-create/docx-pipeline) | Markdown → high-quality Chinese DOCX — dual backend + Mermaid rendering + 4 templates | ![Release](https://img.shields.io/github/v/release/redamancy231-create/docx-pipeline) | published |
| [**Claude Skills**](https://github.com/redamancy231-create/claude-skills) | 3 battle-tested Claude Code Skills — session handoff · CLAUDE.md authoring · pre-emptive veto | ![Release](https://img.shields.io/github/v/release/redamancy231-create/claude-skills) | published |

### Quant Engineering

| Project | What it is | Release | Status |
|------|------|:--:|:--:|
| [**ETF Pattern Match — pybind11**](https://github.com/redamancy231-create/etf-pattern-match-pybind11) | pybind11/C++20 accelerated quant strategy core — DTW 34× / pattern matching 53× | ![Release](https://img.shields.io/github/v/release/redamancy231-create/etf-pattern-match-pybind11) | published |
| [**ETF Pattern Match — PyO3**](https://github.com/redamancy231-create/etf-pattern-match-pyo3) | Rust/PyO3 rewrite of ETF pattern matching — API-compatible with C++ original, NRR-2026-023 C++ vs Rust full comparison | ![Release](https://img.shields.io/github/v/release/redamancy231-create/etf-pattern-match-pyo3) | published |
| [**factor-cuda**](https://github.com/redamancy231-create/factor-cuda) | CUDA-accelerated cross-sectional factor analysis — rank / correlation / IC / parameter scan, memory trilogy validated, E2E ~3.0× | ![Release](https://img.shields.io/github/v/release/redamancy231-create/factor-cuda) | published |

---

```mermaid
graph TB
    F["🤖 AI Collaboration Framework<br/>168K chars · Mothership"]
    F --> H["📋 Handbook<br/>50 lessons"]
    F --> R["🔍 Review Toolkit<br/>SOP + templates"]
    F --> P["🧪 Prompt-TDD<br/>Experiment casebook"]
    F --> N["📊 Negative Results<br/>23 entries"]
    F --> S["⚡ Claude Skills<br/>3 battle-tested skills"]
    F --> M["🔬 Methodology Extraction<br/>22-project meta-analysis"]
    D["📄 DOCX Pipeline<br/>Markdown→DOCX"] -.->|standalone tool| F
    A["🎓 M&A Pipeline<br/>8-stage × 5 models"] -.->|application demo| F
    Q["📈 ETF-pybind11<br/>C++ quant acceleration"] -.->|standalone project| F
    Q --> E["🦀 ETF-PyO3<br/>Rust rewrite"]
    C["🚀 factor-cuda<br/>CUDA cross-sectional analysis"] -.->|standalone project| F
```

> **Solid lines** = derived/extracted from the AI Collaboration Framework. **Dashed lines** = standalone tools or application demos.

---

## 📖 Start Here

- **New to Human-AI collaboration?** → [AI 协作框架](https://github.com/redamancy231-create/ai-collaboration-framework)
- **Want battle-tested lessons at a glance?** → [Methodology Handbook](https://github.com/redamancy231-create/methodology-handbook)
- **Designing prompt controlled experiments?** → [Prompt-TDD Methodology](https://github.com/redamancy231-create/prompt-tdd-methodology)
- **Looking for review SOPs and prompt templates?** → [Independent Review Toolkit](https://github.com/redamancy231-create/independent-review-toolkit)
- **Want to see "what doesn't work" in AI experiments?** → [Negative Results Registry](https://github.com/redamancy231-create/negative-results-registry)
- **Need Markdown → DOCX with Chinese typography?** → [DOCX Pipeline](https://github.com/redamancy231-create/docx-pipeline)
- **Want battle-tested Claude Code Skills?** → [Claude Skills](https://github.com/redamancy231-create/claude-skills)
- **Interested in quant engineering?** → [ETF Pattern Match — pybind11](https://github.com/redamancy231-create/etf-pattern-match-pybind11) (C++ original) or [ETF Pattern Match — PyO3](https://github.com/redamancy231-create/etf-pattern-match-pyo3) (Rust rewrite)
- **Building academic pipelines with LLMs?** → [M&A Case Study Pipeline](https://github.com/redamancy231-create/ma-case-study-pipeline)
- **Curious about methodology extraction?** → [Methodology Extraction Methodology](https://github.com/redamancy231-create/methodology-extraction-methodology)

---

## 📫 Let's Connect

- 💬 Open to collaboration on reproducible AI-assisted research and quant engineering tooling
- 🐛 Found a bug or have a suggestion? Open an issue on the relevant repo
- ⭐ If you find my projects useful, consider starring them

---

> [简体中文](README.md) | English | [正體中文](README.zh-Hant.md)