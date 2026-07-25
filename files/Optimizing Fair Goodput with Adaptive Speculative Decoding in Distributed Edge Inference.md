---
title: "Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference"
date: 2025-12-10
type: entity
source: "https://arxiv.org/abs/2512.09963"
tags: [distributed_inference, speculative_decoding, LLM, edge_computing]
---

# Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference

## Summary
Introduces **GOODSPEED**, a distributed inference framework for LLMs that optimizes "goodput" (effective rate of accepted tokens) using adaptive speculative decoding.

## Key Contributions
- **Adaptive Speculative Decoding**: Uses multiple heterogeneous draft servers to generate candidates, verified by a central server.
- **Gradient Scheduling Algorithm**: Dynamically assigns verification tasks to maximize a logarithmic utility function, ensuring proportional fairness across servers.
- **Theoretical Guarantee**: Provably converges to optimal goodput allocation in steady-state conditions.

## Analysis & Results
- **Scalability**: Enables efficient collaboration between distributed draft generators and a central verifier.
- **Performance**: Maintains near-optimal performance under dynamic workloads with bounded error.
- **Verdict**: Critical for scaling LLM inference in resource-constrained edge environments with multiple users.
