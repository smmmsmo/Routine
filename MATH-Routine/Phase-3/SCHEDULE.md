# Phase 3 — Complete 64-week / 1,344-hour schedule

**Scope:** every required topic in [TOPICS.md](TOPICS.md) appears in the timetable below. Resource codes link to [RESOURCES.md](RESOURCES.md). Start **only after Phase 2**. Calendar weeks are sequential learning weeks, not dates from today.

**Time inside EVERY week:** 6 hours selected reading/lectures, 10 hours exercises and mathematical proofs/derivations, 2 hours implementation/difficult problems and 3 hours cumulative review/test = **21 hours**. These hours include all homework; do not attempt entire supplementary textbooks or Stanford's full GPU engineering assignments.

**Work completion:** read the named topic sections of the primary resource, solve representative unseen exercises, reproduce the formulas or core proof, then complete the weekly output. The stated targets are bounded (e.g., introduction, selected example) when appropriate. Final three weeks are inside the 64-week budget.

## A — Matrix and tensor calculus / AD — Weeks 1–5 (5 weeks × 21 h = 105 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 1 | Vector/matrix/tensor notation; shapes; differentials, Jacobians and chain rule | **MC** | Derive and dimension-check two vector-valued derivatives. |
| 2 | Gradients, Hessians, quadratic forms, trace/determinant differentials | **MC** | Derive least-squares gradient and Hessian from differentials. |
| 3 | Softmax, sigmoid, log-sum-exp, cross-entropy, normalization gradients | **MC** | Derive softmax Jacobian and cross-entropy gradient. |
| 4 | Forward- versus reverse-mode autodiff; computational graphs; JVP/VJP | **MC** | Manually differentiate a small computational graph in both modes. |
| 5 | Tensor contractions, matrix inverse/log-det gradients, finite-difference gradient checks; block review | **MC** | Verify matrix derivatives and explain numerical gradient-check failure modes. |

## B — Learning theory and kernels — Weeks 6–11 (6 weeks × 21 h = 126 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 6 | ERM, risk, hypothesis classes, losses, training/test distribution and regularization | **SL** | Write a precise learning problem and risk decomposition. |
| 7 | PAC setting, realizable/agnostic learning, finite hypothesis class bounds | **SL** | Prove a finite-class bound with union bound. |
| 8 | Uniform convergence, Hoeffding applications, sample complexity | **SL** | Derive sample-complexity dependence on ε, δ and |H|. |
| 9 | VC dimension, shattering, growth functions, stability and Rademacher intro | **SL** | Compute VC dimension in basic examples; discuss limitations. |
| 10 | Max-margin learning, primal/dual SVM, KKT, margin guarantees | **SL** | Derive a simple SVM dual and verify KKT conditions. |
| 11 | PSD kernels, feature maps, kernel ridge regression, RKHS examples; block review | **SL** | Prove a simple kernel is PSD and solve a mixed learning-theory test. |

## C — Graphical models and inference — Weeks 12–17 (6 weeks × 21 h = 126 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 12 | Bayesian networks, DAG factorization and conditional independence | **PG** | Factor a distribution and test d-separation examples. |
| 13 | Markov random fields, potentials, factor graphs and normalization | **PG** | Construct factor graph and compare directed/undirected models. |
| 14 | Latent variables, Gaussian mixtures and EM / Jensen lower bound | **PG** | Derive EM updates for an elementary Gaussian-mixture setup. |
| 15 | Exact inference: variable elimination, forward-backward and sum-product on trees | **PG** | Manually compute marginal distributions by message passing. |
| 16 | Variational inference: KL, ELBO, mean-field coordinate updates and reparameterization | **PG** | Derive a mean-field update and explain the objective. |
| 17 | Monte Carlo, importance sampling, MCMC (MH/Gibbs), diagnostics and block review | **PG** | Compare approximate inference methods and pass mixed problems. |

## D — Optimization for machine learning — Weeks 18–22 (5 weeks × 21 h = 105 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 18 | Smoothness, Lipschitz gradients, strong convexity, basic convergence inequalities | **OM** | Prove a descent step under smoothness assumptions. |
| 19 | Gradient descent rates; stochastic gradients, schedules and minibatch variance | **OM** | Explain convergence-rate assumptions and noise effects. |
| 20 | Momentum, accelerated methods, AdaGrad/Adam mathematics and caveats | **OM** | Implement two updates; derive their state recurrences. |
| 21 | Second-order/HVP, Newton/quasi-Newton, clipping, conditioning and line search | **OM** | Compare curvature methods on a quadratic. |
| 22 | Subgradients, proximal steps, constrained/KKT and nonconvex optimization; block review | **OM** | Derive proximal update for L1 and solve final optimization problems. |

## E — Deep-learning mathematics — Weeks 23–28 (6 weeks × 21 h = 126 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 23 | Neural networks as composed affine maps; activation and log-likelihood losses | **DL** | Derive 2-layer network gradients from scratch. |
| 24 | Backpropagation with shared parameters, Jacobians, normalization gradients | **DL** | Compute gradients of a small network on paper and test. |
| 25 | Initialization, gradient instability, learning-rate and conditioning effects | **DL** | Analyze exploding/vanishing gradients in a model. |
| 26 | Regularization, weight decay, dropout, normalization and residual links | **DL** | Explain and mathematically compare regularization methods. |
| 27 | CNN convolution/equivariance, Fourier intuition, approximation capacity | **DL** | Prove simple translation equivariance; state approximation caveats. |
| 28 | Graph neural network/message passing intro; generalization/implicit bias intro; block review | **DL** | Work small graph propagation and pass deep-learning math review. |

## F — Transformer mathematics — Weeks 29–33 (5 weeks × 21 h = 105 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 29 | Autoregressive sequence probabilities, token embeddings and cross-entropy | **TR** | Derive token-level negative log-likelihood and perplexity. |
| 30 | Q/K/V projections, scaled dot-product attention, masks and softmax | **TR** | Compute attention matrices by hand with shapes. |
| 31 | Backprop through attention, multi-head composition, residuals and normalization | **TR** | Derive selected gradients; explain head dimensions. |
| 32 | Positional encodings, encoder/decoder structure and causal factorization | **TR** | Show where positional information enters the computation. |
| 33 | Attention memory/time scaling, KV caching and selected scaling observations; block review | **TR** | Analyze O(n²) attention cost and pass transformer derivation test. |

## G — Generative mathematics — Weeks 34–39 (6 weeks × 21 h = 126 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 34 | Density modeling, autoregressive generation, latent variable objectives | **GE** | Derive log-likelihood for a basic autoregressive model. |
| 35 | VAEs: evidence lower bound, KL, amortized inference and reparameterization | **GE** | Derive ELBO from Jensen's inequality. |
| 36 | Normalizing flows: invertible maps, Jacobian determinants and likelihood | **GE** | Calculate log-density for a simple affine flow. |
| 37 | GANs: minimax objective, optimal discriminator, divergence connection | **GE** | Derive discriminator optimum under idealized conditions. |
| 38 | Energy/score matching intro; diffusion forward/reverse Markov processes | **GE** | Write DDPM forward noising equations and variance statements. |
| 39 | DDPM training/denoising, score-based SDE intuition and model comparisons; block review | **GE** | Compare assumptions, objective and tractability of VAE/flow/GAN/diffusion. |

## H — Reinforcement learning — Weeks 40–43 (4 weeks × 21 h = 84 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 40 | MDPs, discounted return, value functions and Bellman expectation equations | **RL** | Solve a finite 2-state MDP Bellman system. |
| 41 | Optimality Bellman equations; policy iteration/value iteration and convergence | **RL** | Prove contraction for discounted Bellman operator in tabular case. |
| 42 | Monte Carlo, temporal difference, Q-learning, behavior/exploration | **RL** | Derive TD update and discuss off-policy limitations. |
| 43 | Policy gradient identity, REINFORCE, advantage/actor-critic intro; block review | **RL** | Derive policy gradient using log-derivative and solve mixed problems. |

## I — Information theory and coding — Weeks 44–47 (4 weeks × 21 h = 84 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 44 | Entropy, joint/conditional entropy, chain rules and KL/cross-entropy | **IT** | Prove Gibbs inequality in a finite-distribution example. |
| 45 | Mutual information, data processing inequality and entropy bounds | **IT** | Derive MI chain identity and apply DPI. |
| 46 | Source coding, prefix codes, Kraft inequality, channel capacity examples | **IT** | Construct prefix code and compute BSC capacity in a basic setting. |
| 47 | Rate distortion/Fano intro; linear error-correcting codes and Hamming distance; review | **IT** | Work generator/parity-check matrices and pass theory test. |

## J — Advanced algorithms — Weeks 48–52 (5 weeks × 21 h = 105 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 48 | Randomized analysis: indicator variables, concentration, randomized quicksort/hash | **AA** | Derive expected-time bound for one randomized algorithm. |
| 49 | Approximation algorithms: set cover, greedy analysis and ratios | **AA** | Prove logarithmic greedy bound in a selected setting. |
| 50 | Flow/matching review; min-cost flow introduction and reductions | **AA** | Construct a network and prove correctness of reduction. |
| 51 | Online algorithms/competitive analysis; streaming/sampling/sketches intro | **AA** | Analyze an online strategy and simple streaming estimator. |
| 52 | Communication complexity model and lower bound intro; algorithms block review | **AA** | State/prove one elementary lower-bound argument; mixed exam. |

## K — Computability, complexity and crypto foundations — Weeks 53–57 (5 weeks × 21 h = 105 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 53 | DFA/NFA, regular languages, CFG/PDA and closure/pumping examples | **TC** | Prove a simple language is nonregular. |
| 54 | Turing machines, recognizability, decidability, universal computation | **TC** | Specify decider/recognizer and reason about halting. |
| 55 | Diagonalization, halting problem, Rice theorem and mapping reductions | **TC** | Write one undecidability reduction carefully. |
| 56 | P, NP, coNP, NP-completeness, SAT and polynomial reductions | **TC** | Prove a problem NP-complete using a known source problem. |
| 57 | Randomized classes basics, pseudorandomness, one-way functions and RSA/security intro; exam | **TC** | Separate assumptions from proved statements; pass complexity quiz. |

## L — Causality, robustness and shift — Weeks 58–61 (4 weeks × 21 h = 84 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 58 | Causal DAGs, confounding, interventions, potential outcomes and observational assumptions | **CR** | Construct causal graphs and distinguish correlations from effects. |
| 59 | Backdoor adjustment and causal identification limits; randomized experiment connections | **CR** | Derive simple adjustment expression with assumptions. |
| 60 | Covariate/label/concept shift, domain adaptation and calibration | **CR** | Compute a shift-weighting example; assess calibration. |
| 61 | Adversarial robustness, uncertainty and fairness tradeoffs; synthesis test | **CR** | Explain which robustness/causal claims are defensible. |

## M — Phase 3 synthesis and exam — Weeks 62–64 (3 weeks × 21 h = 63 h)

| Week | This week's required topics | Primary resource code | Finish within this week |
|---:|---|---|---|
| 62 | Re-derive softmax/backprop, PAC bound, SVM dual, VI ELBO and Bellman equation | **RV** | Take closed-book mathematical derivation exam and repair gaps. |
| 63 | Re-derive attention shapes, diffusion objective, entropy/DPI and one complexity reduction | **RV** | Take a second mixed proof/problem exam; small reproducible experiment. |
| 64 | Final integrated assessment, cross-track review and Phase 4 prerequisite inventory | **RV** | Record topic coverage, exam results and topics needing repair. |

## Total timeframe reconciliation

| Metric | Value |
|---|---:|
| Week count | **64** |
| Study days | **448** |
| Study hours | **1,344** |
| Subject blocks | **13** |

**Finish rule:** Finish *all assigned scoped topic clusters* and check independently with proof problems. A calendar deadline is a pacing target, not proof of mastery; extend the date for critical gaps. Deeper graduate extensions belong in Phase 4/5.