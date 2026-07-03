# GoodSpeed: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference

**Source:** [arXiv:2512.09963](https://arxiv.org/abs/2512.09963)
**Date:** Dec 2025
**Venue:** Accepted at INFOCOM 2026

## Summary
GoodSpeed is a distributed inference framework designed to accelerate Large Language Model (LLM) inference using adaptive speculative decoding. It employs a central verification server that coordinates multiple heterogeneous draft servers (each running a small language model).

## Key Contributions
- **Adaptive Speculative Decoding:** Uses lightweight draft models to generate candidate tokens, which are then verified by a larger model.
- **Gradient Scheduling Algorithm:** Dynamically assigns token verification tasks to maximize a logarithmic utility function, ensuring proportional fairness across the heterogeneous draft servers.
- **Parallel Processing:** Processes speculative outputs from all draft servers in parallel to optimize both latency and throughput.

## Analysis & Relevance
This paper is highly relevant to Luca's research in **Distributed Edge Inference**. It addresses the computational bottleneck of LLMs at the edge by distributing the "drafting" process across multiple nodes. The focus on "fair goodput" and "proportional fairness" is particularly interesting for heterogeneous edge environments where devices have varying capabilities.

## Status
- [ ] Read full paper
- [ ] Analyze the gradient scheduling algorithm details
- [ ] Evaluate potential applications in split computing scenarios
