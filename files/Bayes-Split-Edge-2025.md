---
title: "Paper Note: Bayes-Split-Edge: Bayesian Optimization for Constrained Collaborative Inference in Wireless Edge Systems"
date: 2026-06-28
tags: [IoT, Edge Computing, Split Computing, Distributed Inference]
---

## Summary
The paper "Bayes-Split-Edge: Bayesian Optimization for Constrained Collaborative Inference in Wireless Edge Systems" (Chakareski & Hashemi, 2025) addresses the challenge of collaborative inference for resource-constrained edge devices (e.g., AR/VR headsets) in wireless networks. 

The authors propose the **Bayes-Split-Edge** framework, which uses Bayesian Optimization to jointly optimize:
1. The neural network split point (where to divide local vs. server-side processing).
2. Transmission power.

This optimization aims to maximize inference utility while strictly adhering to energy and delay constraints.

## Key Contributions
- **Bayesian Optimization Framework:** Introduces an approach that is significantly more sample-efficient than reinforcement learning baselines (e.g., PPO, CMA-ES), requiring at most 20 function evaluations.
- **Hybrid Acquisition Function:** A new acquisition function that balances inference utility, sample efficiency, and constraint violation penalties.
- **Performance:** Evaluations using VGG19 (ImageNet-Mini) and Resnet101 (Tiny-ImageNet) show near-linear convergence and performance matching exhaustive search under tight constraints.

## Analysis for Luca's Research
This paper is highly relevant to Luca's focus on **Distributed Edge Inference** and **Split Computing**. The use of Bayesian Optimization as a sample-efficient alternative to Reinforcement Learning (which often requires thousands of training epochs) offers a practical path for adaptation in dynamic wireless channel environments where model training costs must be kept low.

Link: [https://arxiv.org/html/2510.23503v1](https://arxiv.org/html/2510.23503v1)
