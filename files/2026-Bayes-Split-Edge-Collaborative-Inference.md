# Bayes-Split-Edge: Bayesian Optimization for Constrained Collaborative Inference in Wireless Edge Systems

**Source**: [arXiv:2510.23503](https://arxiv.org/abs/2510.23503)
**Venue**: SEC '25 (ACM/IEEE Symposium on Edge Computing)
**Key Fields**: Split Computing, Distributed Edge Inference, Bayesian Optimization, Resource Allocation

## Summary
Bayes-Split-Edge focuses on collaborative inference for energy-constrained devices (like AR/VR headsets). It uses Bayesian Optimization (BO) to jointly determine the optimal neural network split point and the required transmission power to meet strict energy and delay deadlines.

## Analysis
The paper introduces a **hybrid acquisition function** for BO that handles constraint violations more effectively than standard BO. The results show that it is highly sample-efficient (requiring $\le 20$ evaluations) and achieves near-exhaustive search performance. This makes it practical for real-time adaptation to fluctuating wireless channel conditions.

## Relevance to Luca's Research
Highly relevant to **Split Computing** and **Distributed Edge Inference**, particularly the mathematical optimization of the split point and power management in wireless IoT environments.
