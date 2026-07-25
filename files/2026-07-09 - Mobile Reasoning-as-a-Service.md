---
title: "Mobile Reasoning-as-a-Service via Distributed LLM Inference-Time Scaling"
date: 2026-07-09
type: entity
source: "https://arxiv.org/abs/2607.08116"
tags: [Distributed Edge Inference, Split Computing, LLM, DRL, MoE]
---

# Mobile Reasoning-as-a-Service via Distributed LLM Inference-Time Scaling

## Summary
The paper introduces the **MORES** framework to enable complex LLM reasoning on resource-constrained edge devices. It focuses on *implicit reasoning* (updating hidden states iteratively) and proposes a cooperative inference mechanism where these updates are split between the edge device and a cloud server.

## Key Contributions
- **Split Reasoning**: Partitions the recursive hidden state updates of implicit reasoning across the edge-cloud continuum.
- **Joint Scheduling**: Formulates a joint computation and communication scheduling problem to handle wireless heterogeneity and task demands.
- **MoE-DRL Agent**: Uses a semantic Mixture-of-Experts (MoE)-based Deep Reinforcement Learning algorithm to adaptively allocate resources (recurrent steps and pruning rate).

## Analysis
This work is highly relevant to Luca's research on **Split Computing** and **Distributed Edge Inference**, specifically applying these concepts to the emerging field of LLM inference-time scaling. The use of MoE for routing and DRL for scheduling reflects modern trends in adaptive edge AI.

## Source
- [arXiv:2607.08116](https://arxiv.org/abs/2607.08116)
