# Phase 5 — Best Quality Books, Research Sources and Tools

**Selection:** best-fit research references, whether paid or free, are used via university access when possible. **No single book can act as a complete research curriculum**. Choose **one specialty spine** plus papers, not all 5 track stacks. The weekly resource codes below link to this document and to [SCHEDULE.md](SCHEDULE.md).

## Universal research sources (compulsory for all 32 weeks)

| Code | Resource | Why / how to use |
|---|---|---|
| **READ** | **S. Keshav — *How to Read a Paper*** ([Papers We Love copy and bibliographic record](https://paperswelove.org/papers/how-to-read-a-paper-1b34f63c/)) | Three-pass technique: first skim, then structural reading, then independently reconstruct the result. Use Weeks 4–9. |
| **WRITE** | **Terence Tao — *On writing*** ([author's advice](https://terrytao.wordpress.com/advice-on-writing-papers/)) | Mathematical writing, organizing a result, accurate assumptions, proofs and references. Use in Weeks 2, 9, 27–32. |
| **EXPO** | **Donald Knuth, Tracy Larrabee & Paul Roberts — *Mathematical Writing*** ([Stanford online book](https://www-cs-faculty.stanford.edu/~knuth/klr.html)) | High-standard mathematical exposition and revision. Use in Weeks 27–31. |
| **RESEARCH** | **MIT Mathematics UROP+** ([department's model for supervised projects](https://math.mit.edu/research/undergraduate/urop-plus/)); **MIT guidance on research experience** ([department page](https://math.mit.edu/gummi/Research-experience.html)) | Benchmarks for a small supervised project and an honest 10–20-page exposition; **not an entitlement to a MIT project or mentor**. |
| **SEARCH** | **[arXiv](https://arxiv.org/)**, **[zbMATH Open](https://zbmath.org/)**, **[MathSciNet via AMS/university](https://mathscinet.ams.org/mathscinet/)** | Find original mathematical results, surveys and bibliographic records. Search backward/forward citations and verify versions and errata. Use continually Weeks 1–32. |
| **MLOPEN** | **[OpenReview](https://openreview.net/about)** | Read ML papers and, where venue policy allows, reviews/discussion. Particularly useful in T1; conference/preprint status must be checked. |
| **CITE** | **[Zotero](https://www.zotero.org/)** | Manage PDFs, exact citations, DOI, arXiv identifiers, tags and annotated bibliographies; confirm metadata before publishing. |
| **TEX** | **[LaTeX Project](https://www.latex-project.org/)** and university LaTeX installations or [Overleaf](https://www.overleaf.com/)** | Typeset proofs, theorems, figures and bibliography; version source. |
| **LEAN** | **[Mathematics in Lean](https://leanprover-community.github.io/mathematics_in_lean/)** | Optional formal-checking pathway for a small theorem. Code compiling does not ensure a theorem expresses the intended original claim. |
| **REPRO** | **[ACM artifact evaluation guidance](https://2024.acmmmsys.org/participation/reproducibility/)** (representative published guidance) | For experimental work: scripts, dependencies, seeds, readable instructions, hardware requirements and realistic limitations. |

## One specialty stack — choose exactly one

The following are high-quality research-entry materials. **Read carefully selected chapters needed for one question**, not the entire book. By the time you reach Phase 5, verify available new editions, corrections and scholarship in the field.

### T1 — Optimization / mathematical ML

**Primary depending on problem:**
- **Roman Vershynin — *High-Dimensional Probability: An Introduction with Applications in Data Science*, 2nd ed. (Cambridge, 2026)**: [author's open book and lecture course](https://www.math.uci.edu/~rvershyn/papers/HDP-book/HDP-book.html), [publisher](https://www.cambridge.org/core/books/highdimensional-probability/748AE7D1E34D1EB98E4D96E1659330FA). Strong for concentration, random matrices and probabilistic methods. Choose a theorem in a small, tractable subset.
- **Martin J. Wainwright — *High-Dimensional Statistics: A Non-Asymptotic Viewpoint***: [Cambridge chapter map](https://www.cambridge.org/core/books/abs/highdimensional-statistics/list-of-chapters/66276F30627CC1056C33D60051468183). Strong for proof-driven ML/statistical learning research.
- **Sébastien Bubeck — *Convex Optimization: Algorithms and Complexity***: [arXiv author monograph](https://arxiv.org/abs/1405.4980). Strong for optimization convergence proofs.
- **Shai Shalev-Shwartz & Shai Ben-David — *Understanding Machine Learning: From Theory to Algorithms***: [Cambridge publisher](https://www.cambridge.org/core/books/understanding-machine-learning/3059695661405D25673058E43C8BE2A6). Strong for learning-theory methodology and proof structure.

**Typical starting projects:** test tightness of a finite-sample concentration bound; rederive and verify a convergence guarantee for an explicit loss under precise assumptions; study a special restricted hypothesis class.

### T2 — Algorithms and theoretical CS

- **Sanjeev Arora & Boaz Barak — *Computational Complexity: A Modern Approach***: [authors' free draft](https://theory.cs.princeton.edu/complexity/); advanced theorems and reductions.
- **Motwani & Raghavan — *Randomized Algorithms*** (Cambridge, university library): random variables, tail estimates, randomized proofs and algorithms.
- **Kleinberg & Tardos — *Algorithm Design*** or **CLRS — *Introduction to Algorithms*, 4th ed.** (library): deep correctness and approximation proofs.
- **MIT 6.046J — Design and Analysis of Algorithms**: [OCW](https://ocw.mit.edu/courses/6-046j-design-and-analysis-of-algorithms-spring-2015/).

**Typical projects:** reproduce a randomized algorithm's expectation argument; construct adversarial cases; prove a bound for a restricted family of graphs.

### T3 — Probability / stochastic mathematics

- **Rick Durrett — *Probability: Theory and Examples*** (Cambridge, university library): graduate probability and convergence.
- **David Williams — *Probability with Martingales*** (Cambridge, library): martingale tools.
- **Bernt Øksendal — *Stochastic Differential Equations*** (Springer, library): SDE and Itô topics.
- **Vershynin — *High-Dimensional Probability*, 2nd ed.** ([author's resource](https://www.math.uci.edu/~rvershyn/papers/HDP-book/HDP-book.html)): high-dimensional concentration and random matrix problems.

**Typical projects:** derive a stopping-time probability in a finite model, examine sharpness of a martingale bound, or validate an SDE discretization with honest error statements.

### T4 — Analysis / PDE / functional analysis

- **Haim Brezis — *Functional Analysis, Sobolev Spaces and Partial Differential Equations*** ([Springer](https://link.springer.com/book/10.1007/978-0-387-70914-7)): functional and variational methods.
- **Lawrence C. Evans — *Partial Differential Equations*, 2nd ed.** (AMS, university library): rigorous PDE theory.
- **Stein & Shakarchi — *Fourier Analysis: An Introduction*** (Princeton, library): key transform estimates and convergence.
- **Sheldon Axler — *Measure, Integration & Real Analysis*** ([author's legal PDF](https://measure.axler.net/)): precise measure-theoretic reference.

**Typical projects:** construct a weak formulation of a model equation, verify an elementary energy estimate, or build a counterexample showing a needed regularity condition.

### T5 — Pure algebra / number theory / geometry

- **David S. Dummit & Richard M. Foote — *Abstract Algebra*** (Wiley, library): groups, rings, fields, explicit structures.
- **Michael Artin — *Algebra*** (Pearson, library): structural and geometric algebra.
- **Kenneth Ireland & Michael Rosen — *A Classical Introduction to Modern Number Theory*** (Springer, library): deeper elementary/algebraic-number-theory connections.
- **John M. Lee — *Introduction to Smooth Manifolds*** ([Springer](https://link.springer.com/book/10.1007/978-1-4419-9982-5)): geometry-oriented path.
- **[zbMATH Open](https://zbmath.org/)** and MathSciNet help determine what is already known for a narrowly specified conjecture.

**Typical projects:** classify finite examples with proof, prove a theorem for a special family or produce a rigorous counterexample to a tempting but false claim.

## Weekly resource codes

- **READ:** Keshav / intensive original paper reading.
- **WRITE:** Tao + Knuth et al. mathematical writing.
- **SEARCH:** arXiv + zbMATH Open + university MathSciNet + original papers.
- **SPECIALTY:** **one** selected T1–T5 stack; choose only the chapters needed.
- **VERIFY:** Lean (optional), computational reproducibility sources and carefully specified test cases.
- **REVIEW:** expert comments, expository readings and prior theorem notes.

## Access, research integrity and uncertainty

- University library access is appropriate for paid monographs, MathSciNet, journals and publisher platforms.
- University resources and preprints should be checked for **version, correctness and subsequent errata**.
- Citation trails establish provenance, **not** automatic novelty. A current literature audit and knowledgeable external feedback are required before making originality claims.
- arXiv can have endorsement/eligibility rules for new submitters. Read [arXiv's endorsement help](https://info.arxiv.org/help/endorsement.html) rather than assuming open posting.
- If no mentor is available, prioritize a **correct and well-written expository/reproduction project** rather than inventing a novelty claim.
