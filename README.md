# Under the Hood of Large Language Models

### Mathematical Foundations, Architectural Complexities, and Production Engineering

**Author:** Utkarsh Tripathi  
**Document Type:** Technical White Paper  
**Domain:** Artificial Intelligence, Deep Learning & Distributed Systems  
**Edition:** October 2026

---

## Overview

Large Language Models (LLMs) appear simple at the application layer: a prompt enters an API, and a response is generated. Behind this interface lies a sophisticated system involving probability theory, high-dimensional linear algebra, Transformer architectures, GPU memory management, distributed computing, and inference optimization.

This technical white paper explores the mathematical principles and engineering decisions behind modern Transformer-based LLMs, connecting theoretical foundations with the challenges of deploying AI systems in production environments.

## Read the Paper

**[Read the full technical white paper (PDF)](paper/under-the-hood-of-llms.pdf)**

The complete paper contains mathematical formulations, technical explanations, architectural diagrams, and production-oriented comparisons.

## Topics Covered

### 1. Mathematical Foundations of Transformers
- Autoregressive sequence factorization
- Cross-entropy loss and perplexity
- Byte-Pair Encoding (BPE)
- Rotary Position Embeddings (RoPE)
- Scaled Dot-Product Self-Attention
- Multi-Head Attention, RMSNorm, and SwiGLU

### 2. Scaling and Inference Optimization
- Quadratic attention complexity
- Key-Value (KV) cache memory requirements
- FlashAttention and PagedAttention
- Grouped-Query Attention (GQA)
- Distributed training memory requirements
- Data, tensor, and pipeline parallelism

### 3. Advanced Model Architectures and Alignment
- Sparse Mixture of Experts (MoE)
- Expert routing and load balancing
- Reinforcement Learning from Human Feedback (RLHF)
- Proximal Policy Optimization (PPO)
- Direct Preference Optimization (DPO)

### 4. Efficient Inference and Model Adaptation
- Activation-Aware Weight Quantization (AWQ)
- Speculative decoding
- Low-Rank Adaptation (LoRA)
- Quantized LoRA (QLoRA)
- Parameter-efficient fine-tuning

### 5. Production LLM Engineering
- Hybrid Graph-RAG architectures
- Dense and sparse retrieval
- Reciprocal Rank Fusion (RRF)
- Cross-encoder reranking
- Grammar-constrained decoding
- Finite-State Machine (FSM) logit masking
- Autonomous agentic workflows
- Enterprise architecture trade-offs

## Why This Paper?

The goal is to connect the mathematics of LLMs with the systems engineering required to operate them efficiently.

Rather than treating LLMs as black-box APIs, this paper examines the underlying mechanisms that influence model behavior, memory consumption, inference latency, scalability, and reliability.

It is intended to support deeper technical understanding of how modern language models are trained, optimized, and integrated into real-world applications.

## Intended Audience

This paper is intended for:

- Students exploring advanced AI and machine learning
- Developers building LLM-powered applications
- AI/ML engineers studying Transformer internals
- Researchers interested in model optimization
- Engineers exploring production-grade generative AI systems

Readers should have a basic understanding of linear algebra, probability, deep learning, and neural networks to get the most out of the mathematical sections.

## Repository Structure

```text
under-the-hood-of-llms/
├── README.md
├── LICENSE
├── paper/
│   └── under-the-hood-of-llms.pdf
├── assets/
│   ├── figures/
│   └── diagrams/
├── notes/
└── REFERENCES.md
```

Some directories are intended for supplementary resources and may be added as the repository evolves.

## How to Use This Repository

1. Read the full white paper in the `paper/` directory.
2. Explore the mathematical formulations and architecture diagrams.
3. Use the supplementary notes and references, when available, to investigate individual concepts further.
4. Open an issue to report a typo or suggest an improvement.

## Author

**Utkarsh Tripathi**

Interested in Artificial Intelligence, Machine Learning, LLM architectures, and practical AI engineering.

- GitHub: [@UtkarshTripathi-teach](https://github.com/UtkarshTripathi-teach)
- LinkedIn: [Utkarsh Tripathi](https://www.linkedin.com/in/utkarsh-tripathi-94080335b/)

## Scope and Disclaimer

This document is an educational and technical exploration of LLM architectures and production engineering. Numerical examples, architectural comparisons, and performance estimates should be interpreted within their stated assumptions and configurations rather than as universal benchmarks.

The paper should not be treated as a substitute for the original research papers, official technical documentation, or empirical testing.

## License

The licensing terms for the paper and supplementary materials should be specified in the repository's `LICENSE` file. Unless otherwise stated, all rights to the original article remain with its author.

---

*Exploring the mathematics and engineering behind modern Large Language Models.*
