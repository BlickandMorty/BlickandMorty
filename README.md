# Jordan Conley

Hi! I'm an undergraduate student studying **Chemical Physics at Columbia University**. I previously did military operations in the Texas Army National Guard (and have an active Secret clearance), and I've spent the past year doing contract **AI red-teaming and evaluation work with Mercor**.

My research stack has three connected parts: **AI internals, science, and defensive security**. I build controlled experiments around one shared question: what happens when evidence is conflicting, incomplete, contaminated, or checked by a system that is more reliable than the model's first answer?

**[Open the three-stack research portfolio](https://github.com/BlickandMorty/three-stack-research-portfolio)**

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
* **[Scientific Evidence-State Transport](https://github.com/BlickandMorty/scientific-evidence-state-transport)** — The frozen layer-20 sign held on `31/36` short numeric science pairs but shrank to `17.6%` of its earlier magnitude. A 30-pair longer-chain replication failed (`11/30` expected signs), and a post-hoc layout explanation reversed on 24 untouched bases. I reject robust, layer-specific, and confirmed formatting-interaction claims.
* **[Representation–Causality Gap Audit](https://github.com/BlickandMorty/representation-causality-gap-audit)** — A source-only layer-20 ridge probe went from `100%` entity-CV to `50%` on 120 new-format cases (`0%` REFUTED/CONFLICT). A separately frozen multiformat readout trained on source plus Quill formats then reached `79.2%` macro accuracy on a predeclared third 120-case Mosaic format (CONFLICT `100%`, REFUTED `50%`), while the model head reached `49.2%`. This is readout generalization, not causal control or scientific intelligence.
* **[Component-Edit Bound Audit](https://github.com/BlickandMorty/component-edit-bound-audit)** — A frozen Qwen3 1.7B transcoder-hook locality test. The development-fitted envelope transferred to 87 eligible held-out prompts with `2/87` violations and no PPL drift above `1.0`, but the science slice was inactive and a random decoder direction was slightly stronger on the target margin, so I explicitly reject a universal or semantic-circuit interpretation.
* **[Scientific Reasoning Audit Loops](https://github.com/BlickandMorty/scientific-reasoning-audit-loops)** — A 72-case held-out chemistry/physics/biology study on Qwen3 1.7B. Direct scratchpads scored `61.1%`; a generated self-audit reached `79.2%` (`+18.1` points, paired 95% CI `+6.9` to `+29.2`) but also broke three correct answers. A verifier-gated loop reached `76.4%` with no regressions by design.
* **[Dose-Response Audit Lab](https://github.com/BlickandMorty/dose-response-audit-lab)** — Reproducible 4PL/IC50 Monte Carlo studies separating outlier robustness from concentration-window identifiability. Missing a plateau made roughly 69–74% of potency fits at least twofold wrong even when the optimizer reported success.
* **[Proof-Carrying Policy Evals](https://github.com/BlickandMorty/proof-carrying-policy-evals)** — A defensive ALLOW/DENY/ESCALATE benchmark with a deterministic oracle, SHA-256 receipts, and 96 metamorphic cases that distinguish stable reasoning from being consistently wrong. A frozen exploratory 48-case certificate-format comparison improved Qwen3 from 39.6% to 54.2% and reduced unauthorized ALLOWs 2→1, but its paired lower CI was 0.0, so I do not call it a confirmed control.
* **[Lattice State Consistency Lab](https://github.com/BlickandMorty/lattice-state-consistency-lab)** — An exhaustive finite-state test of my data-as-lattice idea. The product representation passed every lattice law and 2,592 migration homomorphism checks; the original cross-system validity subset failed both closures. A frozen 84-rule follow-up then mapped the repair boundary: `all_of` prerequisites preserve both operations, multi-item `any_of` is join-only, `at_most_one_of` is meet-only, and `exactly_one_of` is neither.
* **[Sheaf Connectome Sanity Lab](https://github.com/BlickandMorty/sheaf-connectome-sanity-lab)** — A preregistered 360-graph test of my HELIOS T32 criterion across synthetic AI circuits, biochemical pathways, and defensive security zones. The algebraic H0 identity passed, but the claimed positive raw-gap/modularity direction was decisively reversed (`rho = -0.972`, 95% CI `-0.977` to `-0.963`); shuffled-label and degree-preserving controls collapsed near zero.
* **[Interrupt Router Calibration Lab](https://github.com/BlickandMorty/interrupt-router-calibration-lab)** — A frozen selective-classification test on 108 unseen science, defensive-security, and records prompts. A raw-logit-margin fallback reduced unauthorized ALLOW decisions from `4` to `1` at a `24.1%` interrupt rate without changing `38.9%` accuracy, but always-ESCALATE tied that accuracy and exposed a weak, class-skewed base classifier.

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
