---
title: "Bayes-Split-Edge: Bayesian Optimization for Constrained Collaborative Inference in Wireless Edge Systems"
date: 2026-06-09
type: source
source: "https://arxiv.org/html/2510.23503v1"
tags: [split-computing, bayesian-optimization, wireless-edge, resource-allocation]
---

# Bayes-Split-Edge

## Summary
This paper proposes **Bayes-Split-Edge**, a framework that jointly optimizes the neural network split point and transmission power to maximize inference utility while satisfying strict energy and delay constraints in wireless edge networks.

## Key Contributions
- **Joint Optimization**: Simultaneously selects the optimal split layer and transmit power.
- **Hybrid Acquisition Function**: Introduces a novel acquisition function for Bayesian Optimization (BO) that integrates expected improvement, uncertainty-based exploration, and soft penalties for constraint violations.
- **Sample Efficiency**: Achieves up to 2.4× reduction in evaluation cost compared to standard BO and outperforms baselines like CMA-ES, DIRECT, and PPO.
- **Convergence**: Demonstrates near-linear convergence and matches exhaustive search performance even under tight constraints.

## Analysis & Relevance
Extremely relevant to Luca's interest in **Split Computing** and **Distributed Edge Inference**. The use of BO for sample-efficient resource allocation in dynamic wireless environments is a strong practical approach for AR/VR and wearable devices where training-heavy RL (like PPO) is too slow to converge.
