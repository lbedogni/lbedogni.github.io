# Bayes-Split-Edge: Bayesian Optimization for Constrained Collaborative Inference in Wireless Edge Systems

**Source:** [arXiv:2510.23503](https://arxiv.org/html/2510.23503v1)
**Date:** 2025
**Field:** Split Computing, Wireless Edge Computing, Constrained Optimization

## Summary
The paper proposes **Bayes-Split-Edge**, a framework designed to optimize the collaborative inference of neural networks between a resource-constrained mobile device (e.g., AR/VR headset) and an edge server. The core challenge addressed is balancing local computation and data transmission to satisfy strict energy and delay constraints.

## Key Contributions
- **Joint Optimization:** Simultaneously optimizes the neural network split point and the transmit power.
- **Bayesian Optimization (BO):** Leverages BO for sample-efficient black-box optimization, which is crucial for dynamic wireless environments where the objective function lacks a closed-form expression.
- **Hybrid Acquisition Function:** Introduces a novel acquisition function that integrates expected improvement, uncertainty-based exploration, and soft penalties for constraint violations.

## Results & Analysis
- **Efficiency:** Achieves up to a **2.4× reduction in evaluation cost** compared to standard BO.
- **Performance:** Outperforms baselines such as CMA-ES, DIRECT, and PPO, matching the performance of exhaustive search even under tight constraints.
- **Convergence:** Demonstrates near-linear convergence, requiring a maximum of 20 function evaluations.

## Relevance to Luca's Research
Highly relevant to **Split Computing** and **Distributed Edge Inference**. Specifically, the use of Bayesian Optimization for real-time resource allocation in the Cloud-Edge-Device continuum is a powerful technique for handling the uncertainty of wireless channels.
