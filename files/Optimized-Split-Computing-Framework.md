# Optimized Split Computing Framework for Edge and Core Devices

- **Venue**: IEEE Transactions on Vehicular Technology / arXiv 2509.06049v1
- **Keywords**: Split Computing, FFNN, Edge-Core Hierarchy, Resource Optimization
- **Link**: [arXiv:2509.06049](https://arxiv.org/abs/2509.06049v1)

## Summary
This research proposes an optimization framework for Feed-Forward Neural Network (FFNN) models partitioned across a three-tier hierarchy: User Equipment (UE), edge nodes, and core nodes. The framework aims to minimize the computational footprint on the UE (memory and CPU) while keeping the overall inference time within acceptable limits. The authors provide a heuristic strategy to solve this partitioning problem without needing to retrain the model.

## Analysis
While less "dynamic" than the UAV swarm approach, this paper provides a rigorous optimization perspective on the UE $\to$ Edge $\to$ Core pipeline. The reported reduction in UE memory (33.6%) and CPU (60%) footprints is significant for actual device deployment.
