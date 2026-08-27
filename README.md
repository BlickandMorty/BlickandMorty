# Jordan Conley

Hi! I'm an undergraduate student studying **Chemical Physics at Columbia University**. I previously did military operations in the Texas Army National Guard (and have an active Secret clearance), and I've spent the past year doing contract **AI red-teaming and evaluation work with Mercor**.

I spend most of my time building tools, testing where AI models mess up, and exploring math and science.

---

### What I Know vs. What I'm Learning

I believe in being 100% upfront about where my skills actually are today:

| Skill / Language | Where I'm At | How I Actually Use It |
| :--- | :--- | :--- |
| **AI Red-Teaming & Eval** | `[████████████████░░░░] 80%` | My main strength. I've spent months writing adversarial prompts, catching hallucinations, testing edge cases, and grading model reasoning at Mercor. |
| **HTML & CSS** | `[██████████████░░░░░░] 70%` | Very comfortable with page structure, clean layouts, and styling. |
| **Python** | `[██████████░░░░░░░░░░] 48%` | I know the core fundamentals (loops, functions, lists/dicts, tests, basic scripts), and I'm actively using it to get better every day. |
| **Lean 4 / Formal Math** | `[██████░░░░░░░░░░░░░░] 30%` | I understand the basics and have completely worked through the first 7 core theorems in my EML project. The rest is my personal study syllabus. |
| **C++** | `[███░░░░░░░░░░░░░░░░░] 15%` | Basic syntax and reading header files. |
| **Swift & Rust** | `[██░░░░░░░░░░░░░░░░░░] 10%` | I understand how the architectures fit together, but I use AI to help write the low-level code while I learn the basics. |

---

### The Math & Research Repos (Keeping It 100% Real)

> *"In an age of abundant AI-generated proofs, human understanding may become more valuable than proof generation itself."*  
> — **Terence Tao** (August 2026)

If you look at my math or Lean 4 repos, you'll see a lot of theorem candidates and formal code. I want to be totally clear about how they were made:

* **I used AI to help map out and scaffold these theorem ideas.** It's easy for an AI to generate hundreds of lines of math symbols, but raw generation doesn't mean understanding.
* **What I actually understand:** Right now, I have human mastery over the **first 7 foundational theorems and core identities** in EML. 
* **The rest is my study guide:** The other ~200 theorem candidates are my long-term curriculum. I'm using my coursework at Columbia to slowly learn, verify, and make sense of the math for real.
* **Red-teaming in public:** Working through these repos is also how I test where LLMs succeed at logic and where they hallucinate or make invalid assumptions.

---

### My Projects

#### Current Research Program — Evidence Under Pressure

My current work connects three things I care about: AI internals, scientific
measurement, and defensive security. The shared question is what happens to a
decision when evidence is conflicting, contaminated, missing, or mixed with an
instruction that should not have authority.

* **[Evidence-Conflict Circuits](https://github.com/BlickandMorty/evidence-conflict-circuits)** — A 256-case Qwen3 study built from four-valued evidence logic. A preregistered layer-20 intervention generalized to 48 held-out pairs (`+13.38` forward, `−13.26` reverse), while a sparse-transcoder follow-up produced an informative null result that I report rather than hide.
* **[Dose-Response Audit Lab](https://github.com/BlickandMorty/dose-response-audit-lab)** — Reproducible 4PL/IC50 Monte Carlo studies separating outlier robustness from concentration-window identifiability. Missing a plateau made roughly 69–74% of potency fits at least twofold wrong even when the optimizer reported success.
* **[Proof-Carrying Policy Evals](https://github.com/BlickandMorty/proof-carrying-policy-evals)** — A defensive ALLOW/DENY/ESCALATE benchmark with a deterministic oracle, SHA-256 receipts, and 96 metamorphic cases that distinguish stable reasoning from being consistently wrong.

#### Everyday Tools & Experiments
* **[LivingBrain](https://github.com/BlickandMorty/LivingBrain)** — A memory engine experiment in Rust based on how biological brains remember and forget.
* **[Epistemos Instant Recall](https://github.com/BlickandMorty/epistemos-instant-recall)** — A fast local search engine for notes and documents.
* **[Windows Resilience Suite](https://github.com/BlickandMorty/windows-resilience-suite)** — Clean PowerShell scripts for Windows performance, maintenance, and backup health.
* **[DataSight-AI](https://github.com/BlickandMorty/DataSight-AI)** — A simple tool to check CSV files for missing data, outliers, and schema errors.
* **[Epistemos Prompt Lab](https://github.com/BlickandMorty/epistemos-prompt-lab)** — A collection of prompt templates I tested for research, memory, and agent evaluation.

#### AI Evaluation & Math Notes
* **[EML-star Epistemos](https://github.com/BlickandMorty/eml-star-epistemos)** — An Exp-Minus-Log and branch-analysis toolkit. My latest audit formally falsifies the closed grammar's density claim: without a coordinate terminal every generated term is input-independent, so Stone-Weierstrass point separation fails.
* **[Epistemos Labs](https://github.com/BlickandMorty/epistemos-labs)** — Experimental workspace for testing deterministic tools, receipts, and agent safety boundaries.
* **[Ethos Eval](https://github.com/BlickandMorty/ethos-eval)** — An offline tool for testing LLM behavior against clear, reproducible rules.
* **[OLS vs Gradient Descent](https://github.com/BlickandMorty/ols-vs-gradient-descent)** — A simple, reproducible comparison between classic OLS math and gradient descent.

---

### How I Like to Work

I try to keep things grounded: **test first, check the facts, don't pretend to know things I don't, and fix mistakes quickly.** 

AI is an amazing tool to help brainstorm, scaffold code, and learn faster, but the real work is human understanding.
