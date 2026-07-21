# AI/ML Project Ladder

Projects convert theory into evidence. Each project should have a clear problem statement, baseline, reproducible setup, evaluation plan, error analysis, and README.

## Levels

- [Beginner Projects](Beginner.md): focused implementations and small end-to-end applications
- [Intermediate Projects](Intermediate.md): stronger evaluation, multiple models, and practical data problems
- [Advanced Projects](Advanced.md): research, systems, deployment, and specialization work

## Standard Project Structure

```text
project-name/
├── README.md
├── pyproject.toml or requirements.txt
├── configs/
├── data/               # metadata or download instructions, not private/raw data
├── notebooks/          # exploration only
├── src/
├── tests/
├── models/             # usually ignored; document acquisition
├── reports/
└── scripts/
```

## Required README Sections

1. Problem and motivation
2. Dataset and data limitations
3. Success metrics
4. Baseline
5. Method
6. Experimental setup
7. Results
8. Error analysis
9. Limitations and responsible-use considerations
10. Reproduction instructions
11. Future improvements

## Project Quality Checklist

- [ ] Clear target and success criteria
- [ ] Valid train/validation/test design
- [ ] Simple baseline included
- [ ] Reproducible environment and seeds
- [ ] Data validation and leakage checks
- [ ] Appropriate metrics
- [ ] Experiment log
- [ ] Error and subgroup analysis
- [ ] Tests for important code
- [ ] Useful visualizations
- [ ] Honest limitations
- [ ] Demo, API, or report when appropriate

## Portfolio Recommendation

Choose depth over quantity. A strong final portfolio can contain:

- 2 polished classical ML projects
- 1 computer vision project
- 1 NLP project
- 1 LLM/RAG project
- 1 deployed end-to-end system
- 1 research reproduction
- 1 major capstone
