# Optimized Split Computing Framework for Edge and Core Devices

**Venue:** IEEE Transactions on Vehicular Technology / arXiv:2509.06049
**URL:** https://arxiv.org/abs/2509.06049

## Summary
This work proposes an optimization framework for partitioning Feed-Forward Neural Network (FFNN) models across a three-tier hierarchy: User Equipment (UE), edge-located nodes, and core-located nodes. The goal is to minimize the computational burden on the UE while keeping the overall inference time within acceptable limits.

## Key Contributions
- **Three-Tier Partitioning:** Moves beyond the binary (device/server) split to a UE -> Edge -> Core continuum.
- **Heuristic Optimization:** Provides an efficient strategy to determine the optimal split points across the tiers.
- **Resource Reduction:** Reduces UE memory footprint by 33.6% and CPU footprint by 60% without requiring model retraining.

## Analysis & Relevance
Relevant to **Distributed Edge Inference** and **Split Computing**. It operationalizes the "compute continuum" concept, showing how to dynamically balance the load across different levels of the network. The fact that it requires no retraining makes it highly practical for deployment of existing models.
# [Optimized Split Computing Framework for Edge and Core Devices](https://arxiv.org/html/2509.06049)

**Date:** September 2025
**Field:** Split Computing, Edge Computing, Neural Network Optimization

## Summary
This paper proposes a generalized optimization framework for Split Computing (SC) applied to Feed-Forward Neural Networks (FFNNs) to reduce the computational burden on User Equipment (UE).

### Key Concepts:
- **Multi-Point Splitting:** Unlike traditional split computing (which uses a single split point between UE and server), this framework allows an arbitrary number of splitting points across the UE, edge nodes (base stations), and core network nodes.
- **Joint Optimization:** The framework optimizes the splitting points by jointly considering:
    - Computational and memory capacities of all nodes.
    - Link quality (bandwidth/MCS) between sequential nodes.
- **Heuristic Strategy:** Provides an efficient heuristic to find feasible splitting points without needing to retrain the model.

## Analysis & Relevance
Directly relevant to **Split Computing** and **Distributed Edge Inference**. The ability to distribute a model across a pipeline of nodes (UE $\to$ Edge $\to$ Core) rather than a binary split is a significant step toward more flexible edge-cloud collaboration.

**Result:** Demonstrates a reduction in UE memory/CPU footprint by 33.6% to 60% while maintaining inference time constraints.

**Potential Application:** useful for deploying complex FFNNs on very low-end IoT devices by leveraging the hierarchical nature of cellular networks.
