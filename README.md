# Evidence-First AI, Formal Methods, and Systems Engineering

I build tools that make AI-assisted work easier to inspect, falsify, replay, and govern. My projects connect AI evaluation and prompt engineering with formal methods, mathematical experimentation, deterministic software, and practical systems tooling.

---

### 🔬 Epistemic Transparency & Learning-in-Public Note

> *"In an age of abundant AI-generated proofs, human understanding may become more valuable than proof generation itself. [...] The scarce resource in mathematics shifts from finding proofs to making sense of them."*  
> — **Terence Tao**, *Mathematics in the Age of AI (2026)*

**Project Status & Methodology:**
* **AI-Augmented Scaffolding:** Mathematical formalisms, Lean 4 candidate declarations, and EML structure trees across these repositories were initially explored and scaffolded using frontier AI models as cognitive force multipliers.
* **Radical Honesty & Public Learning:** Rather than claiming independent mathematical authorship or discovery over generated formalisms, this corpus serves as my open curriculum and public research notebook. As an undergraduate studying Chemical Physics at Columbia University, I am systematically deconstructing, understanding, and learning the underlying formal logic, proof steps, and physical mechanisms step-by-step.
* **Active Model Evaluation & Failure Mode Logging:** A central objective of this work is **AI Red-Teaming in Formal Reasoning**—benchmarking where LLMs succeed at generating valid proof terms versus where they produce subtle hallucinations, invalid branch assumptions, or empty tautologies.

#### 📊 Formal Verification & Learning Progress Tracker

| Track | Status | Progress | Notes |
| :--- | :--- | :--- | :--- |
| **AI Formal Scaffolding** | Complete | `[██████████] 100%` | 246 theorem/lemma candidate declarations mapped across Lean 4 corpus |
| **Automated Compiler Check** | Verified | `[████████░░] 85%` | 209 declarations checked with formal proof terms |
| **Systematic Human Study** | In Progress | `[███░░░░░░░] 30%` | Active undergraduate coursework & self-directed proof deconstruction |
| **LLM Formal Failure Logging** | Active | `[███████░░░] 70%` | Ongoing documentation of where LLMs hallucinate branch cuts / proof steps |

---

## Selected Work

### Systems & Applied Tooling

- **[LivingBrain](https://github.com/BlickandMorty/LivingBrain)** — A biological-style memory engine in Rust featuring Ebbinghaus decay, Poincaré hyperbolic vault topology, tiered sub-millisecond retrieval, and trajectory metrics.
- **[Epistemos Instant Recall](https://github.com/BlickandMorty/epistemos-instant-recall)** — A cross-platform Rust engine fusing title ranking, Tantivy BM25, and deterministic vector similarity for explicit search and ambient note recall.
- **[Windows Resilience Suite](https://github.com/BlickandMorty/windows-resilience-suite)** — Audit-first PowerShell modules for Windows performance, maintenance, cleanup, backup integrity, gaming power, and workspace policy monitoring.
- **[DataSight-AI](https://github.com/BlickandMorty/DataSight-AI)** — Cross-platform CSV data-quality auditor for missing values, outliers, schema risks, and explainable review.
- **[Epistemos Prompt Lab](https://github.com/BlickandMorty/epistemos-prompt-lab)** — 17 tested prompt packs for research, evaluation, memory, agent instructions, approval gates, and durable loops.

### AI Evaluation, Formal Methods & Learning Logs

- **[Epistemos Labs](https://github.com/BlickandMorty/epistemos-labs)** — A tested Rust workspace for evidence gates, deterministic receipts, numerical witnesses, scoped agents, and retrieval experiments.
- **[EML-star Epistemos](https://github.com/BlickandMorty/eml-star-epistemos)** — An attributed mathematical research derivative of Andrzej Odrzywołek's Exp-Minus-Log operator (`eml(x,y) = exp(x) - ln(y)`) and Anthony Monnerot's anti-holomorphic companion, featuring immutable IR, branch witnesses, Lean structure, and AI-assisted exploratory tooling.
- **[Epistemos](https://github.com/BlickandMorty/Epistemos)** — Research intelligence and evidence-traceable reasoning systems.
- **[Ethos Eval](https://github.com/BlickandMorty/ethos-eval)** — Offline-first deterministic LLM behavior evaluation with explicit weighted rules and reproducible reports.
- **[OLS vs Gradient Descent](https://github.com/BlickandMorty/ols-vs-gradient-descent)** — Reproducible numerical comparison of closed-form OLS and batch gradient descent, with convergence tests and benchmark falsifiers.

## How I Work

My recurring engineering loop is:
`frame -> inspect -> propose -> test -> falsify -> repair -> verify -> stop`

I separate observation from inference, attach tests or evidence to completion claims, preserve uncertainty, and prefer bounded failure over confident invention. In research repositories, “formal,” “analytic,” “conditional,” “numerical,” and “open” are deliberately different statuses.

## About the Repositories & AI Collaboration

Several public repositories were assembled by consolidating earlier Epistemos research, experiments, and task histories. AI tools assist with formal scaffolding, syntax implementation, testing, and audit work. The human learning journey, experimental validation, and commitment to radical transparency remain my personal responsibility.
