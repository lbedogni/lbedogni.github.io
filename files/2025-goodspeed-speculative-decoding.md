# GoodSpeed: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference

**Source:** [arXiv:2512.09963](https://arxiv.org/abs/2512.09963)
**Date:** Dec 2025
**Field:** Distributed Edge Inference, LLM Acceleration, Speculative Decoding

## Summary
Introduces GOODSPEED, a framework to accelerate Large Language Model (LLM) inference in distributed environments using adaptive speculative decoding.

## Core Innovations
1. **Distributed Speculative Decoding**: Employs a central verification server coordinating multiple heterogeneous "draft" servers (small LLMs) that generate candidate tokens in parallel.
2. **Gradient Scheduling Algorithm**: Dynamically assigns token verification tasks using a logarithmic utility function to ensure **proportional fairness** across different draft servers.
3. **Fluid Sample Path Analysis**: Provides theoretical proof that the system converges to optimal goodput (effective rate of accepted tokens) in steady-state.

## Results
- Scalable and efficient solution for multi-server speculative decoding.
- Maintains near-optimal performance under dynamic workloads.

## Analysis for Luca
Relevant to **Distributed Edge Inference** and **Split Computing**. It applies the concept of splitting the model (draft vs. verification) across a distributed set of nodes to maximize throughput while maintaining fairness—a key challenge in multi-tenant edge clusters.
