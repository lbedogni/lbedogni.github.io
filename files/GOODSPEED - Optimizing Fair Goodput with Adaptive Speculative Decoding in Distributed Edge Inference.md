---
title: "GOODSPEED: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference"
date: 2025-12-10
type: entity
source: "https://arxiv.org/abs/2512.09963"
tags: [Distributed Inference, Speculative Decoding, LLM, Edge Computing, INFOCOM 2026]
---

# GOODSPEED: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference

## Summary
GOODSPEED is a distributed inference framework designed to accelerate Large Language Model (LLM) inference using **adaptive speculative decoding**. It addresses the challenge of maintaining high "goodput" (the effective rate of accepted tokens) and fairness in a multi-user environment where a central verification server coordinates multiple heterogeneous draft servers.

## Key Contributions
- **Distributed Architecture**: Utilizes a central verification server and multiple heterogeneous draft servers (running smaller LMs) to generate candidate tokens in parallel.
- **Gradient Scheduling Algorithm**: Dynamically assigns token verification tasks by maximizing a logarithmic utility function, ensuring proportional fairness across the diverse set of draft servers.
- **Convergence & Performance**: Provably converges to optimal goodput allocation in steady-state and maintains near-optimal performance under dynamic workloads with bounded error.
- **Outcome**: Streamlines both latency and throughput for multi-server speculative decoding.

## Analysis
This paper is highly relevant to the "Distributed Edge Inference" and "Split Computing" themes. By distributing the "drafting" phase of speculative decoding across the edge, it reduces the bottleneck on the central server and allows for heterogeneous hardware (different SLMs on different edge nodes) to contribute to the inference process. The focus on "fairness" is crucial for multi-tenant edge environments where different users or devices might have varying resource capacities.
