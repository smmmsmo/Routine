# Phase 1 — Quality-First University Books and Resources

**Policy:** select the strongest teaching resources for mathematical depth, clarity, exercises and proof quality **without regard to whether they are paid or free**. Use the university library for paid editions. **Do not read every reference cover to cover**. One main course/book per block + selected supplementary proof problems fits the [64-week schedule](SCHEDULE.md).

## Primary books and university course resources

| Code | Weeks | Primary spine | Outstanding supplemental resources | What to finish |
|---|---|---|---|---|
| **PR** | **1–6: Proofs and logic** | **Daniel J. Velleman — *How to Prove It: A Structured Approach*, 3rd ed.** ([Cambridge official book page](https://www.cambridge.org/highereducation/books/how-to-prove-it/6D2965D625C6836CD4A785A2C843B3DA)). Excellent bridge from computation to proof, with extensive original exercises. | **Richard Hammack — *Book of Proof*** ([author's freely available book](https://richardhammack.github.io/BookOfProof/)); MIT 6.042J proofs and logic resources ([MIT OCW](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-spring-2015/)). | Logic, quantifiers, sets, functions/relations, proof types, induction, countability introduction. |
| **C1** | **7–17: Calculus I** | **Stewart, Clegg & Watson — *Calculus: Early Transcendentals*, 9th ed.** ([Cengage publisher](https://faculty.cengage.com/titles/9781337613927)). Strong comprehensive STEM calculus presentation with many problems. | **MIT 18.01SC Single Variable Calculus** ([complete independent-study course](https://ocw.mit.edu/courses/18-01sc-single-variable-calculus-fall-2010/)); **Michael Spivak — *Calculus*, 4th ed.** (select demanding proof problems if ready). | Stewart Ch. 1–4 (functions, limits/derivatives, rules and applications); initial integral ideas Ch. 5 when introduced. |
| **C2** | **18–28: Calculus II** | **Stewart, Clegg & Watson — *Calculus: Early Transcendentals*, 9th ed.** ([publisher/TOC](https://faculty.cengage.com/titles/9781337613927)). Continuity avoids switching notation and integrates applications. | **MIT 18.01SC** (above), especially integration, techniques and series; **Tom M. Apostol — *Calculus*, Vol. I** (Wiley, optional rigorous companion, not another whole course). | Selected Stewart Ch. 5–8, 10–11 (integration/uses, parametric/polar curves, sequences/series); selected Ch. 9 only for separable-ODE illustration. |
| **LA** | **29–40: Linear algebra** | **Gilbert Strang — *Introduction to Linear Algebra*, 6th ed.** ([Wellesley-Cambridge Press official](https://wellesleycambridge.com/books/introduction-to-linear-algebra-6th-edition)). Strong first-pass understanding of matrices, four spaces, eigenvectors and SVD. | **MIT 18.06SC Linear Algebra** ([independent study, lectures/problem sets/exams](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/)); **Sheldon Axler — *Linear Algebra Done Right*, 4th ed.** ([author's open-access edition](https://linear.axler.net/)) for abstract proofs in selected sections. | Strang/MIT: all core computational linear-algebra units, eigen/least-squares/SVD; Axler: selective vector-space/linear-map/eigen/inner-product proofs, **not** all advanced chapters. |
| **MC** | **41–51: Multivariable and vector calculus** | **MIT 18.02SC Multivariable Calculus** ([complete independent-study course](https://ocw.mit.edu/courses/18-02sc-multivariable-calculus-fall-2010/)). Complete with vectors, partial derivatives, multiple integrals, vector calculus, exam solutions. | **Stewart, Clegg & Watson — *Calculus: Early Transcendentals*, 9th ed.** ([Cengage TOC](https://faculty.cengage.com/titles/9781337613927)), Ch. 12–16; optional **Hubbard & Hubbard — *Vector Calculus, Linear Algebra, and Differential Forms: A Unified Approach*** (Matrix Editions, library) for conceptual depth. | MIT 18.02SC four units; Stewart Ch. 12–16 selected; compute and interpret gradient, Jacobian, Hessian, double/triple integrals, line/surface integrals, Green/Stokes/divergence. |
| **DM** | **52–61: Discrete and mathematical CS** | **MIT 6.042J Mathematics for Computer Science**, Lehman, Leighton & Meyer course text and exercises ([MIT OCW](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-spring-2015/)). Excellent for proof-driven combinatorics, graph theory, modular arithmetic, recurrences and elementary probability. | **Kenneth H. Rosen — *Discrete Mathematics and Its Applications*** (McGraw Hill, university library) for additional exercises; **MIT 6.006 Introduction to Algorithms** ([official OCW](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/)) **selected first lectures/problems only** for correctness and runtime. **Graham, Knuth & Patashnik — *Concrete Mathematics*** (Pearson, library) optional challenge, not required. | Selected MIT 6.042J topics on counting, recurrences, number theory, graph theory and introductory discrete probability; 6.006 selected basic algorithm correctness/analysis only. |
| **RV** | **62–64: Final consolidation** | Return to the **same primary sources and MIT exams**, not a new textbook. | Spivak/Axler challenging examples, 6.042J problem sets and mixed papers as appropriate. | Mixed proofs and independent unseen problem sets across all six subjects; final qualifying assessment and prerequisite gaps. |

## Why this is stronger than just collecting free links

- **Velleman** directly trains proof literacy, the key prerequisite for Phase 2 real analysis and abstract algebra.
- **Stewart** supplies one deep, exercise-rich calculus spine for both differential and integral calculus; **MIT 18.01SC** supplies recitations and checked exams. **Spivak** supplements proof difficulty but must not displace elementary exercise fluency.
- **Strang** develops the computational and geometric linear algebra essential for ML; **Axler** sharpens abstract vector-space and transformation proofs. MIT 18.06SC provides assessment material.
- **MIT 18.02SC** is especially coherent for vector calculus; **Stewart Ch. 12–16** is aligned with the same subjects.
- **MIT 6.042J** is mathematical rather than merely a coding course; it provides the right reasoning base for later algorithms, probability, theoretical CS and discrete research.

These choices are **high-quality, best-fit selections**, not a claim that a single author is universally best for every student. Paid books can be borrowed from your university; legal open texts are equally good when they fit the goal.

## Correct use of supplementary resources

- **For every 21-hour week:** ~6h selective reading/lectures, 10h written exercises/proofs, 2h small implementation or hard problems, 3h spaced review/closed-book test.
- Choose reading by the [assigned weekly topic](SCHEDULE.md). Chapter names vary between printings; match by section title if library edition differs.
- **Prioritize solved problems and written reasoning** over hours spent watching videos.
- Use **one primary book**; consult a supplementary text only for a hard conceptual gap or a more challenging proof.
- For self-assessment, use *unseen* MIT problems and book exercises; do not read solutions before attempting them.
- Python/NumPy/Matplotlib/SymPy are suitable for validation; **never replace proof with a numerical plot**.

## Phase 1 → Phase 2 readiness checklist

- Can reconstruct basic proofs, work with logical quantifiers and justify induction.
- Can solve calculus applications, convergence-test questions and basic Taylor expansions.
- Can explain eigenvectors, orthogonality, rank–nullity, least-squares projection and SVD.
- Can take gradients/Jacobians, solve multiple-integral problems and explain standard vector-calculus theorems.
- Can prove combinatorial identities, analyze recurrences, reason about graph structure and justify elementary algorithm correctness.

## University library checklist

Request the latest institutionally accessible print/eBook edition of Velleman (3e), Stewart/Clegg/Watson (9e), Strang (6e), Rosen and optional Spivak/Apostol/Hubbard. **Do not buy everything**. MIT OCW/author legal-open resources remain supplementary or primary where they excel. Recheck course availability when study actually starts.
