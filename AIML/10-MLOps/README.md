# MLOps and Production AI

## Reproducibility and Project Structure

- Git workflows, environments, dependency locking, configuration, and secrets management
- Separating notebooks, source code, tests, data references, models, and reports
- Deterministic seeds, data snapshots, lineage, and reproducible commands
- Unit, integration, data, model, and end-to-end testing

## Experiment and Model Management

- Experiment tracking, parameters, metrics, artifacts, and comparisons
- Dataset and model versioning
- Model registries, approval stages, documentation, and model cards
- Hyperparameter search and resource tracking

## Serving

- Batch, online, streaming, and edge inference patterns
- FastAPI services, request validation, preprocessing parity, and error handling
- Docker images, health checks, logging, queues, caching, and autoscaling concepts
- CPU/GPU placement, batching, mixed precision, quantization, ONNX, and inference optimization

## Automation

- Data validation and feature pipelines
- Training, evaluation, packaging, and deployment pipelines
- CI checks, continuous delivery, scheduled retraining, and rollback
- Infrastructure and cloud fundamentals
- Kubernetes concepts when scale requires it

## Monitoring

- Service latency, throughput, errors, resource use, and availability
- Input quality, schema changes, drift, prediction distributions, and performance decay
- Ground-truth delays, feedback collection, alert thresholds, and retraining decisions
- Training-serving skew, shadow deployment, canary releases, and A/B tests

## Governance and Reliability

- Privacy, access control, auditability, retention, and responsible data use
- Bias and subgroup monitoring
- Incident response, fallback behavior, and human review
- Cost, carbon, and operational trade-offs

## Required Builds

1. Reproducible training command with configuration and tests
2. Experiment tracking and model registry workflow
3. Containerized prediction API
4. CI pipeline for tests and quality checks
5. Monitoring or drift-detection dashboard
6. End-to-end deployment with a documented rollback plan

## Mastery Checklist

- [ ] A new machine can reproduce my experiment.
- [ ] Training and serving use consistent preprocessing.
- [ ] My service has tests, validation, logging, and health checks.
- [ ] I version data, code, configuration, and model artifacts.
- [ ] I monitor both system and model quality.
- [ ] I can safely deploy, compare, and roll back model versions.
