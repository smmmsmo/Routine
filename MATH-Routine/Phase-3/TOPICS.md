# Phase 3 — Full topic and subtopic syllabus

**64 weeks · 1,344 hours**. This is the complete *required scoped syllabus*; [SCHEDULE.md](SCHEDULE.md) assigns every topic to weeks. Terms such as “introduction” explicitly limit depth: no claim of completing all research literature.

## A. Matrix calculus and automatic differentiation (Weeks 1–5, 105 h)

### A1 — Multivariate and matrix differentials
- Scalar, vector, matrix and tensor notation; broadcasting and dimension conventions.
- Total differentials; directional derivatives and Fréchet derivative **intro**.
- Gradients, Jacobians, Hessians, Hessian-vector products.
- Chain rule for compositions of vector-valued functions and computational graphs.
- Elementwise differentiation versus operator-level differentiation.

### A2 — Useful identities and derivatives
- Trace/determinant identities and their domain assumptions.
- Quadratic forms, least-squares loss, covariance and norm derivatives.
- Log determinant of positive-definite matrices and matrix-inverse differential (basic).
- Derivatives of softmax, cross-entropy, sigmoid, log-sum-exp and normalization.
- Gradient checking using finite differences; limitations due to floating-point error.

### A3 — AD and tensor intuition
- Forward mode (Jacobian-vector products) and reverse mode (vector-Jacobian products).
- Backpropagation as reverse-mode automatic differentiation.
- Computational cost and memory tradeoffs; gradient accumulation.
- Elementary tensor contractions, shapes, and Einstein-summation notation.
- Nondifferentiability, subgradients and numerical stability basics.

## B. Statistical learning theory, kernels and SVMs (Weeks 6–11, 126 h)

### B1 — Learning formulation
- Supervised learning setup; training/test distributions, hypothesis classes and losses.
- Empirical versus expected risk; empirical risk minimization (ERM).
- Overfitting, bias/variance, regularization, validation and data leakage.
- Agnostic and realizable PAC learning; sample complexity.

### B2 — Generalization
- Hoeffding's inequality **statement and applications**, union bound.
- Finite-class uniform convergence, generalization bounds and ERM guarantees.
- Growth functions, shattering and VC dimension.
- Rademacher complexity, stability and margin bounds: **introductory bounds and intuition**.
- No-free-lunch limitations and distributional assumptions.

### B3 — Geometric and kernel methods
- Linear models, large-margin classifiers, soft-margin SVM objective.
- Convex duality and KKT for SVMs; support-vector interpretation.
- Positive semidefinite kernels, feature maps and kernel trick.
- RKHS **definition and selected examples**, not full functional-analytic theory.
- Kernel ridge regression, regularization, validation.

## C. Probabilistic graphical models and inference (Weeks 12–17, 126 h)

- Directed graphical models/Bayesian networks, conditional independence, factorization.
- Undirected graphical models/Markov random fields; potentials and normalizing constants.
- Basic graph separation and Markov properties; factor graphs.
- Latent-variable models, Gaussian mixtures, hidden Markov models, state-space intuition.
- EM algorithm derivation, Jensen inequality and ELBO motivation.
- Exact inference: variable elimination, sum-product belief propagation on chains/trees.
- Variational inference: KL minimization, mean-field approximation, coordinate ascent.
- Reparameterization trick where applicable; gradient-based VI.
- Monte Carlo estimation, rejection and importance sampling; variance concerns.
- Markov chain Monte Carlo: Metropolis–Hastings and Gibbs sampling, convergence diagnostics **intro**.
- Approximation tradeoffs; compare exact, variational and sampling methods.

## D. Optimization for ML (Weeks 18–22, 105 h)

- Smoothness, Lipschitz gradients, strong convexity and condition numbers.
- Gradient descent descent lemma, basic convergence rates under assumptions.
- Stochastic optimization: unbiased gradients, minibatches, variance, noise and schedules.
- Momentum, Nesterov acceleration, AdaGrad/Adam: mathematical update rules and caveats.
- Newton, quasi-Newton, Hessian-free/HVP and conjugate-gradient methods **intro**.
- Nonsmooth regularization, subgradients, proximal gradient/ISTA.
- Constrained optimization/KKT, convex duality and regularization review.
- Nonconvex critical points, saddle points and local minima; guarantees versus heuristics.
- Gradient clipping, normalized gradients, numerical stability and diagnostic plots.

## E. Mathematical deep learning (Weeks 23–28, 126 h)

- Perceptrons and multilayer networks as compositions of affine maps/nonlinearities.
- Loss functions as negative log-likelihood; cross-entropy and maximum likelihood.
- Backpropagation derivation for fully connected networks and shared parameters.
- Initialization, exploding/vanishing gradients, conditioning.
- Normalization, dropout, weight decay and residual connections.
- Approximation capacity and universal approximation **statement/intuitive proof structure**.
- Generalization and implicit regularization **intro**.
- Convolution, kernels and equivariance; CNN operators.
- Embeddings, graph convolution/message passing and permutation invariance **intro**.
- Model evaluation, calibration and controlled comparisons; training stability.

## F. Transformers and sequence models (Weeks 29–33, 105 h)

- Sequence probabilities, autoregressive factorization, teacher forcing.
- Embeddings, token distributions and positional encoding.
- Scaled dot-product attention, queries/keys/values and matrix shape proofs.
- Softmax derivative, attention gradients and masking.
- Multi-head attention, feed-forward blocks, normalization and residual paths.
- Decoder-only/encoder-only/encoder-decoder mathematical distinctions.
- Causal language-model loss, perplexity and cross-entropy.
- Self-attention quadratic sequence complexity, memory bounds, KV caching **intro**.
- Alternative position mechanisms, sparse/local attention **selected ideas**.
- Scaling laws and compute/parameter/data tradeoffs **introductory empirical analysis**, not hard guarantees.
- Understand a small transformer mathematically; no mandatory large GPU training.

## G. Generative-model mathematics (Weeks 34–39, 126 h)

- Density estimation, likelihood, autoregressive factorization and sampling.
- Latent-variable models, variational inference and amortized inference.
- VAE: marginal likelihood, ELBO, reparameterization and KL terms.
- Normalizing flows: change-of-variables, Jacobian determinant, invertible maps.
- GAN minimax objectives, optimal discriminator derivation (under simplifying assumptions), divergence connection.
- Energy-based models and score matching **intro**.
- Diffusion discrete forward/noise process, reverse denoising and DDPM training objective.
- Score-based models and SDE/ODE connections **conceptual introduction**, not graduate stochastic calculus.
- Compare likelihood availability, sampling cost and approximation assumptions.
- Evaluation limitations for high-dimensional generative models.

## H. Reinforcement-learning mathematics (Weeks 40–43, 84 h)

- Markov decision processes; states, actions, transition kernels, rewards and discounting.
- Bellman expectation and optimality equations; contraction intuition.
- Policy evaluation/iteration and value iteration with finite-state convergence.
- Monte Carlo/temporal-difference learning, Q-learning and exploration.
- Policy gradients via log-derivative identity.
- Advantage functions, baselines, actor-critic **intro**.
- Off-policy importance weighting, model-based RL **intro**.
- Function approximation instability and sample efficiency issues.

## I. Information theory and coding (Weeks 44–47, 84 h)

- Self-information, entropy, joint/conditional entropy and chain rule.
- KL divergence, cross-entropy, Gibbs inequality; mutual information.
- Data processing inequality and Markov chains; selected derivations.
- Source coding: prefix codes, Kraft inequality and Shannon coding theorem **selected proof**.
- Channel models, binary symmetric channel, channel capacity **basic examples**.
- Rate–distortion **definition and example**, Fano's inequality **statement/application**.
- Error-correcting codes: Hamming distance, linear block codes, generator and parity-check matrices; elementary bounds.
- Connections to ML loss functions, representation learning and generalization.

## J. Advanced algorithms and probabilistic analysis (Weeks 48–52, 105 h)

- Refresher: asymptotic bounds, recurrences, amortized analysis, rigorous correctness.
- Randomized algorithms, indicator variables, expectation, tail bounds, probability of failure.
- Randomized quicksort, hashing and skip lists **selected cases**.
- Concentration-based performance estimates.
- Advanced graph algorithms: flow/matching, min-cost flow **intro**.
- Randomization and approximation; greedy/set cover approximation analysis.
- Online algorithms and competitive ratio **intro**.
- Streaming algorithms: sampling, sketches, sublinear memory intuition.
- Communication complexity **basic model and one lower bound example**.
- Formal reduction/correctness proofs for selected algorithms.

## K. Automata, computability, complexity, cryptographic foundations (Weeks 53–57, 105 h)

- Formal languages and DFA/NFA; regular expressions and closure.
- Context-free grammars and pushdown automata: recognition basics.
- Turing machines, effective computation, Church–Turing thesis (status and meaning).
- Decidable and recognizable languages; halting problem.
- Mapping reductions, Rice's theorem and diagonalization **selected proofs**.
- Time and space complexity; P, NP, coNP, NP-hardness and NP-completeness.
- Polynomial-time reductions, SAT and 2–3 classic reductions with proofs.
- BPP/RP **intro**, randomness and derandomization vocabulary.
- One-way functions and pseudorandom generators **definitions/assumptions**.
- Basic computational versus information-theoretic security; modular arithmetic and RSA conceptual proof obligations.
- Open problems (P vs NP etc.) are not resolved here.

## L. Causality, robustness and distribution shift (Weeks 58–61, 84 h)

- Association versus causation; statistical confounding and selection bias.
- Directed acyclic graphs, structural causal models, interventions and do-notation.
- Back-door adjustment **selected examples**; identifiability limitations.
- Potential outcomes and randomized experiments: link to statistical inference.
- Covariate, label and concept shift; in-/out-of-distribution generalization.
- Domain adaptation and invariance **intro**.
- Adversarial perturbations and local robustness **intro**.
- Calibration, uncertainty, selective prediction, fairness tradeoffs **selected cases**.
- Clearly separate empirical claims from identifiable causal effects.

## M. Synthesis and qualifying tasks (Weeks 62–64, 63 h)

- Re-derive gradients, generalization bounds, SVM duality, ELBO and Bellman equations.
- Reconstruct a transformer attention forward/backward shape analysis.
- Prove or carefully justify a coding theorem, algorithmic reduction and a complexity classification.
- Reproduce one small mathematical experiment (not full research infrastructure).
- Explain limitations, assumptions, open mathematical questions and prerequisites for Phase 4.
- Mixed exams and repairs; target ≥80% before Phase 4.

## Scope honesty

The target is **complete coverage of the above named items at the indicated depth within 1,344 hours**, NOT completion of every research paper, textbook chapter or subfield. Measure-theoretic stochastic calculus, advanced circuit lower bounds, deep cryptographic constructions, rigorous large-model scaling theory and graduate causal-identification theory require later specialization.
