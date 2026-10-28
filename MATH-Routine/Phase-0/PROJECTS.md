# Phase 0 — Mathematics + Python projects

**Only one project is required to pass Phase 0**; the others are optional. These hours are **already inside** the 336-hour Phase 0 budget, mainly Weeks 11–15. The repository is the schedule/learning tracker, not a substitute for separate coding repositories.

## Required outcome

Produce one small, reproducible repository/notebook with:
- [ ] `README.md`: question, mathematics, formulas, definitions and domain assumptions.
- [ ] `requirements.txt` (if using packages), minimal run instructions.
- [ ] Python script or notebook that can be rerun in a clean environment.
- [ ] At least 5 manual expected-value test cases.
- [ ] At least 2 graphs or tabular outputs supporting an explanation.
- [ ] A numerical or domain edge-case check.
- [ ] 1–2 paragraphs: where the method fails or is limited.
- [ ] Evidence that you solved the underlying algebra before coding.

## Project A — Function family and transformation explorer (recommended)

**Best for:** rebuilding forgotten algebra, logarithms and trigonometry.

### Mathematics
- Compare `x^2`, `(x-2)^2+3`, `2^x`, `log_2(x)`, `sin(x)`, `2sin(x-pi/4)`.
- Identify domain, range, symmetry, intercepts, maxima/minima when relevant, period/asymptote.
- Explain why log requires positive input, why translation modifies intercepts and how sin amplitude/phase affect a graph.

### Tasks
1. Draw or predict each graph on paper.
2. Write a Python function for each model; reject/skip invalid logarithm inputs.
3. Use NumPy/Matplotlib to plot each on an appropriate bounded domain.
4. Compare predicted and computed intercepts/values.
5. Supply a README table with domains/ranges and at least two explanation paragraphs.

### Acceptance tests
- `f(x)=x²`: f(0)=0, f(2)=4.
- `g(x)=(x-2)²+3`: g(2)=3.
- `h(x)=2^x`: h(0)=1.
- `log_2(x)`: log_2(1)=0, log_2(8)=3; reject x<=0.
- `sin(x)`: sin(0)=0, sin(pi/2)=1 (floating-point tolerance).
- Explain that graphing a finite window is not a proof of global behavior.

## Project B — Numerical derivative laboratory

**Best for:** limits and introductory calculus.

### Mathematics
For a differentiable function f, compare the forward difference `(f(x+h)-f(x))/h` with its exact derivative for h = 1, 0.1, 0.01, 0.001. Discuss truncation and floating-point errors without claiming arbitrarily small h is always better.

### Tasks
1. Derive exact derivatives for `x²`, `x³` and `sin(x)` using learned rules.
2. Implement a forward difference function.
3. At x=1 or x=2, make an error table across step sizes.
4. Plot absolute error vs step size (with a safe axis scale).
5. Explain why the approximation improves initially and why roundoff can matter at extreme scales.

### Acceptance tests
- For `f(x)=x²` at x=2, exact derivative=4.
- With h=0.1, forward derivative=4.1 (up to floating-point tolerance).
- With h=0.01, forward derivative=4.01.
- Reject h=0, or handle it explicitly with a clear error.

## Project C — Growth, logarithms and inversion

**Best for:** practical modeling and log confidence.

### Mathematics
Model `N(t)=N0*a^t` with a>0; derive how many steps it takes to reach target M:
`t=log(M/N0)/log(a)` for a>0, a≠1, M/N0>0. Discuss special cases and interpretation when a<1.

### Tasks
1. Derive the inverse formula by taking logarithms.
2. Plot growth and decay for three positive bases.
3. Implement a solver that checks domains and handles a=1 separately.
4. Test starting amounts and targets, report floating-point tolerance.
5. Explain why logarithms linearize exponential growth.

### Acceptance tests
- N0=100, a=2, M=800 -> t=3.
- N0=100, a=0.5, M=25 -> t=2.
- a=1 with M≠N0 has no solution.
- Negative N0 or target is outside this positive-population model.

## Rubric (100 points)

| Item | Points |
|---|---:|
| Mathematical derivation, assumptions and domain | 30 |
| Correct implementation with tests | 25 |
| Verification, uncertainty/error analysis | 20 |
| Explanatory plots and README | 15 |
| Independent reflection and limitations | 10 |
| **Total** | **100** |

**Pass:** >=80 points with no mathematical domain violations or fabricated results. Upload code to your own coding location as appropriate and link it in the Phase 0 tracker. Project alone cannot override an exam category failure.

## Optional enrichment (not required for gate)

- Python tool that generates random variations of logarithm/trigonometry questions and checks answers.
- A numerical Riemann sum visualizer for x² and x³.
- A small geometry simulator testing Pythagoras for random right triangles.
- Proof notebook: induction for arithmetic sequences, triangle identities, exponent laws.

## Safety against shallow learning

Do not copy a plotting library result and call it an explanation. The goal is: **derive → predict → implement → test → explain**.
