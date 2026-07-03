---
title: "GoodSpeed: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference"
date: 2025-12-10
type: entity
source: "https://arxiv.org/abs/2512.09963"
tags: [distributed-inference, LLM, speculative-decoding, goodput, fairness]
---

# GoodSpeed: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference

## Summary
GOODSPEED is a distributed inference framework for Large Language Models (LLMs) that optimizes "goodput" (the rate of accepted tokens) and ensures fairness across multiple heterogeneous draft servers collaborating with a central verification server.

## Key Contributions
- **Adaptive Speculative Decoding**: Uses lightweight draft models to generate candidates, verified by a larger model.
- **Gradient Scheduling Algorithm**: Dynamically assigns verification tasks to maximize a logarithmic utility function, ensuring proportional fairness.
- **Parallel Processing**: Verifies speculative outputs from all draft servers in parallel to reduce latency and increase throughput.

## Results
- Provably converges to optimal goodput allocation in steady-state.
- Maintains near-optimal performance under dynamic workloads with bounded error.
- Accepted at INFOCOM 2026.

## Analysis for Luca
Relevant to **Distributed Edge Inference**, specifically for LLMs. The focus on "fair goodput" and heterogeneous server coordination is a critical aspect of scaling edge inference.
