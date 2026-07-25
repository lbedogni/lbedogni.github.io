---
title: "GoodSpeed: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference"
date: 2025-12-10
type: entity
source: "https://arxiv.org/abs/2512.09963"
tags: [Distributed Edge Inference, LLM, Speculative Decoding, Fairness]
---

# GoodSpeed: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference

## Summary
GoodSpeed is a distributed inference framework designed to accelerate Large Language Model (LLM) inference using adaptive speculative decoding. It coordinates multiple heterogeneous draft servers (running small LMs) with a central verification server.

## Key Analysis
- **Problem:** High computational demand of LLMs and the need for fairness and high goodput (accepted token rate) in multi-user, distributed environments.
- **Solution:** 
    - **Adaptive Speculative Decoding:** Draft servers generate candidates; verification server validates them.
    - **Gradient Scheduling:** A novel algorithm that maximizes a logarithmic utility function to ensure proportional fairness across servers.
    - **Parallel Processing:** Processes outputs from all draft servers in parallel to reduce latency.
- **Results:** Provably converges to optimal goodput allocation in steady-state and maintains near-optimal performance under dynamic workloads.
- **Significance:** Provides a scalable and fair solution for multi-server speculative decoding, making LLMs more viable for distributed edge inference.
