# Large Language Models

## Transformer Internals

- Token embeddings, vocabulary design, positional information, and context windows
- Queries, keys, values, scaled dot-product attention, causal masks, and multi-head attention
- Residual connections, normalization, feed-forward networks, and output heads
- Encoder-only, decoder-only, and encoder-decoder architectures
- Next-token prediction, masked modeling, and sequence-to-sequence objectives
- Scaling, data quality, memorization, and compute constraints

## Adaptation

- Prompting, few-shot learning, structured outputs, and context management
- Supervised fine-tuning and instruction tuning
- LoRA, QLoRA, adapters, and parameter-efficient fine-tuning
- Preference data, reward models, RLHF, and direct preference optimization concepts
- Quantization, distillation, pruning, batching, caching, and inference optimization

## Retrieval-Augmented Generation

- Document parsing, cleaning, chunking, metadata, and indexing
- Sparse, dense, and hybrid retrieval
- Embeddings, vector indexes, reranking, query rewriting, and context assembly
- Citations, grounding, retrieval metrics, answer metrics, and faithfulness evaluation

## Tool-Using Systems

- Function calling, tool schemas, state, memory, and workflow orchestration
- Deterministic workflows versus open-ended agents
- Permission checks, confirmation boundaries, rate limits, and audit logs
- Failure recovery, repeatable operations, and human oversight

## Evaluation and Responsible Use

- Golden datasets, unit tests, model-based grading, and human evaluation
- Accuracy, relevance, faithfulness, robustness, latency, throughput, and cost
- Hallucination, privacy, unsafe instructions, and untrusted external content
- Access controls, testing, monitoring, and layered safeguards

## Required Builds

1. Implement a minimal attention layer and transformer block.
2. Build a RAG system with retrieval and generation evaluated separately.
3. Fine-tune a small model or task head using PEFT.
4. Build a tool-using workflow with explicit permission checks.
5. Compare model quality, latency, and cost across configurations.

## Mastery Checklist

- [ ] I can derive attention dimensions and masking behavior.
- [ ] I understand pretraining, instruction tuning, preference tuning, and retrieval.
- [ ] I can diagnose retrieval failure separately from generation failure.
- [ ] I can design repeatable LLM evaluations.
- [ ] I understand quantization and context-window trade-offs.
- [ ] I can design tool use with appropriate permissions and safeguards.
