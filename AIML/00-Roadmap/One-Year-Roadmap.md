# One-Year AI & Machine Learning Roadmap

This plan assumes roughly **15–20 focused hours each week**. Adjust the pacing when university exams or major projects require it, but keep the sequence: foundations first, systems later.

## Month 1 — Python, Tools, and Mathematical Orientation

### Learn

- Python syntax, functions, classes, modules, environments, exceptions, iterators, generators, and type hints
- NumPy arrays, broadcasting, vectorization, indexing, and linear algebra operations
- pandas data loading, cleaning, transformation, grouping, and joins
- Matplotlib-based data visualization
- Git, GitHub, Linux shell basics, Jupyter, VS Code, and reproducible environments
- Mathematical notation, functions, sets, sums, products, logarithms, and proof basics

### Build

- A data exploration notebook on a public dataset
- Linear regression from scratch with NumPy
- A clean Python package containing reusable preprocessing utilities

### Exit Criteria

- Write vectorized NumPy instead of unnecessary Python loops
- Use Git branches and meaningful commits
- Explain train, validation, and test splits
- Derive and implement mean squared error

## Month 2 — Linear Algebra, Calculus, Probability, and Statistics

### Learn

- Vectors, matrices, dot products, norms, projections, rank, inverse, eigenvalues, eigenvectors, SVD, and PCA
- Derivatives, partial derivatives, gradients, Jacobians, Hessians, chain rule, and Taylor approximation
- Random variables, common distributions, expectation, variance, covariance, conditional probability, and Bayes' theorem
- Sampling, estimators, confidence intervals, hypothesis tests, maximum likelihood, MAP estimation, and the central limit theorem
- Gradient descent, stochastic gradient descent, momentum, adaptive optimization, constraints, and regularization

### Build

- Gradient descent visualizations
- PCA from scratch
- Maximum-likelihood estimation examples

### Exit Criteria

- Explain why matrix multiplication represents composition
- Apply the chain rule to a multilayer function
- Distinguish likelihood from probability
- Explain bias, variance, uncertainty, and regularization

## Month 3 — Supervised Machine Learning I

### Learn

- Problem framing and baseline construction
- Linear and polynomial regression
- Ridge, Lasso, and Elastic Net
- Logistic regression
- k-nearest neighbors
- Naive Bayes
- Data preprocessing, encoding, scaling, missing values, outliers, and feature engineering
- MAE, MSE, RMSE, accuracy, precision, recall, F1, ROC-AUC, PR-AUC, log loss, and calibration

### Build

- House-price regression project
- Spam or sentiment classifier
- Reusable scikit-learn pipelines with cross-validation

### Exit Criteria

- Choose metrics based on business and error costs
- Detect leakage and invalid validation designs
- Explain the effect of regularization
- Compare linear and non-linear baselines

## Month 4 — Supervised Machine Learning II and Unsupervised Learning

### Learn

- Decision trees and pruning
- Random forests and bagging
- Gradient boosting, XGBoost, LightGBM, and CatBoost concepts
- Support vector machines and kernels
- k-means, hierarchical clustering, DBSCAN, and Gaussian mixture models
- PCA, t-SNE, and UMAP concepts and limitations
- Hyperparameter optimization and error analysis
- Class imbalance, threshold selection, interpretability, and fairness basics

### Build

- Customer churn prediction
- Customer segmentation
- Kaggle-style tabular competition with a documented experiment log

### Exit Criteria

- Explain bagging versus boosting
- Diagnose underfitting and overfitting
- Select a suitable clustering method
- Interpret feature importance cautiously

## Month 5 — Neural Networks and PyTorch

### Learn

- Perceptrons, multilayer networks, activation functions, and loss functions
- Forward propagation, computational graphs, and backpropagation
- Initialization, normalization, dropout, weight decay, early stopping, and learning-rate schedules
- Tensors, autograd, Dataset, DataLoader, modules, optimizers, checkpoints, and inference in PyTorch
- GPU training, mixed precision, reproducibility, and debugging training loops

### Build

- A neural network from scratch using NumPy
- A complete PyTorch training pipeline
- An image or tabular classifier with experiment tracking

### Exit Criteria

- Derive backpropagation for a small network
- Write and debug a training loop without copying a template blindly
- Read loss curves and identify common optimization failures

## Month 6 — Computer Vision

### Learn

- Image representations, augmentation, convolution, padding, stride, pooling, and receptive fields
- LeNet, AlexNet, VGG, ResNet, DenseNet, and EfficientNet ideas
- Transfer learning and fine-tuning
- Object detection: R-CNN family, SSD, and YOLO concepts
- Segmentation: fully convolutional networks, U-Net, and Mask R-CNN concepts
- Vision transformers and self-supervised vision basics

### Build

- Transfer-learning image classifier
- Object detection application
- Image segmentation project

### Exit Criteria

- Calculate convolution output shapes and parameter counts
- Explain residual connections
- Choose between classification, detection, and segmentation formulations

## Month 7 — Natural Language Processing

### Learn

- Text normalization, tokenization, subwords, vocabularies, and language modeling
- Bag-of-words, TF-IDF, n-grams, and classical text classifiers
- Word2Vec, GloVe, FastText, and contextual embeddings
- RNNs, LSTMs, GRUs, sequence-to-sequence learning, and attention
- Encoder and decoder transformers
- BERT-style and GPT-style pretraining objectives
- Text classification, named-entity recognition, question answering, summarization, and semantic search

### Build

- Classical and transformer text classifiers
- Semantic search system
- Question-answering or summarization application

### Exit Criteria

- Explain tokenization trade-offs
- Distinguish static and contextual embeddings
- Explain why attention improves long-range modeling

## Month 8 — Transformers and Large Language Models

### Learn

- Scaled dot-product attention, multi-head attention, positional information, residual streams, normalization, and feed-forward blocks
- Decoder-only, encoder-only, and encoder-decoder architectures
- Pretraining, instruction tuning, supervised fine-tuning, preference optimization, and RLHF concepts
- LoRA, QLoRA, parameter-efficient fine-tuning, quantization, batching, and inference constraints
- Prompt design, structured outputs, function calling, and tool use
- Retrieval-augmented generation, chunking, embeddings, reranking, citations, and grounding
- LLM evaluation: task metrics, human evaluation, model-based evaluation, robustness, safety, latency, and cost

### Build

- Transformer components from scratch
- RAG application with evaluation
- Fine-tune a small open model or classifier using PEFT
- Tool-using assistant with explicit safeguards

### Exit Criteria

- Derive attention tensor shapes
- Explain pretraining versus fine-tuning versus retrieval
- Evaluate hallucination and retrieval quality separately

## Month 9 — Generative AI and Multimodal Systems

### Learn

- Autoencoders and latent representations
- Variational autoencoders and the ELBO intuition
- GAN objectives and training instability
- Diffusion forward and reverse processes
- Conditioning, classifier-free guidance, latent diffusion, and sampling
- Contrastive multimodal learning, image-text embeddings, captioning, speech, and multimodal transformers

### Build

- Autoencoder or VAE
- Small GAN experiment
- Diffusion-model notebook or controlled image-generation workflow
- Multimodal search or image-captioning project

### Exit Criteria

- Compare VAE, GAN, autoregressive, and diffusion approaches
- Explain latent-space interpolation and conditional generation

## Month 10 — Reinforcement Learning

### Learn

- Agents, environments, states, actions, rewards, returns, policies, and value functions
- Markov decision processes and Bellman equations
- Dynamic programming, Monte Carlo methods, temporal-difference learning, SARSA, and Q-learning
- Deep Q-networks, replay buffers, target networks, policy gradients, actor-critic, and PPO
- Exploration, reward design, instability, offline RL, and evaluation concerns

### Build

- Tabular Q-learning agent
- DQN agent in a simple environment
- PPO or actor-critic experiment

### Exit Criteria

- Derive Bellman expectation and optimality equations
- Explain on-policy versus off-policy learning
- Recognize reward hacking and unstable evaluation

## Month 11 — MLOps and Production AI

### Learn

- Data and model versioning
- Experiment tracking and artifact management
- Packaging, testing, configuration, logging, and reproducibility
- FastAPI model serving, Docker, queues, caching, and batch inference
- CI/CD, cloud basics, GPU serving, ONNX, quantization, and optimization
- Model registries, monitoring, drift, data quality, feedback loops, rollback, and retraining
- Security, privacy, abuse prevention, and responsible deployment

### Build

- Containerized inference API
- Automated training and evaluation pipeline
- Monitoring dashboard or drift detector
- End-to-end deployed ML application

### Exit Criteria

- Reproduce an experiment from a clean environment
- Deploy a versioned model with tests and monitoring
- Explain training-serving skew and rollback strategy

## Month 12 — Research, Specialization, and Capstone

### Learn

- Efficient paper reading and literature search
- Experimental design, ablations, baselines, uncertainty, and statistical reporting
- Reproduction and replication
- Scientific writing, figures, tables, citations, and limitations
- Choose one specialization: LLMs, computer vision, NLP, reinforcement learning, trustworthy AI, multimodal AI, causal ML, graph ML, or recommender systems

### Build

- Reproduce one research paper or a meaningful subset
- Complete one production-quality capstone
- Write a technical report and project README
- Prepare a portfolio presentation and demonstration

### Exit Criteria

- Defend design decisions and trade-offs
- Report negative results honestly
- Explain the capstone to both technical and non-technical audiences

## Continuous Habits Throughout the Year

- Solve mathematics exercises every week.
- Maintain concise notes and a glossary.
- Read one paper every one or two weeks after Month 4.
- Use Git and document all significant experiments.
- Participate in at least one competition or open-source project.
- Revisit old projects and improve their testing, evaluation, and documentation.
- Keep a monthly retrospective in the progress tracker.

## Final Portfolio Minimum

- Two polished classical ML projects
- One computer vision project
- One NLP project
- One LLM/RAG project
- One generative or multimodal project
- One reinforcement-learning experiment
- One deployed end-to-end ML system
- One research reproduction
- One substantial capstone
