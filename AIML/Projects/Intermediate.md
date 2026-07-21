# Intermediate Projects

These projects require stronger experimental design, multiple components, and realistic evaluation.

## 1. Churn or Credit-Risk System

- Build a leakage-safe temporal or grouped split when appropriate.
- Compare calibrated linear and tree-based models.
- Include threshold selection, subgroup analysis, interpretability, and business-cost reasoning.

## 2. Object Detection Application

- Fine-tune a modern detector on a custom or public dataset.
- Evaluate mAP, class-level errors, localization errors, and inference speed.
- Provide an image/video demo.

## 3. Semantic Search Engine

- Build lexical, dense, and hybrid retrieval baselines.
- Add reranking and a labeled evaluation set.
- Analyze failures by query type and document length.

## 4. Document Question Answering with RAG

- Parse and chunk documents, attach metadata, retrieve, rerank, and generate cited answers.
- Evaluate retrieval recall separately from answer correctness and faithfulness.
- Add tests for unsupported questions and poor retrieval.

## 5. Image Segmentation System

- Train a U-Net-style model.
- Evaluate IoU/Dice, inspect boundary failures, and compare augmentation choices.
- Include reproducible inference visualizations.

## 6. Fine-Tuned Small Language Model

- Select a narrow task and prepare a high-quality dataset.
- Use parameter-efficient fine-tuning.
- Compare against prompting and retrieval baselines.
- Report quality, latency, memory use, and limitations.

## 7. Time-Series Forecasting Pipeline

- Use rolling validation, naive/seasonal baselines, classical models, and a neural model.
- Diagnose drift and uncertainty.
- Avoid random splits that leak future information.

## 8. End-to-End ML API

- Train, version, package, and serve a model with FastAPI and Docker.
- Add validation, tests, logging, health checks, and a small monitoring view.

## Completion Standard

Complete at least three, including:

- [ ] one vision or NLP project;
- [ ] one LLM/RAG or advanced retrieval project;
- [ ] one deployed service;
- [ ] experiment tracking and reproducible commands;
- [ ] explicit error analysis and limitations.
