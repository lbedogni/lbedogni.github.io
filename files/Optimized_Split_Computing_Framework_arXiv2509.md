# Optimized Split Computing Framework for Edge and Core Devices (arXiv 2509.06049)

**Source:** [arXiv:2509.06049](https://arxiv.org/abs/2509.06049v1)

## Summary
The paper proposes an optimization framework for partitioning Feed-Forward Neural Network (FFNN) models across a hierarchy: User Equipment (UE) $\to$ Edge Nodes $\to$ Core Nodes. The goal is to minimize the UE's computational footprint while containing overall inference time.

## Key Contributions
- **Hierarchical Partitioning:** Moves beyond simple binary splits by distributing model sections across three levels of the network.
- **Optimization Heuristic:** Provides an efficient heuristic strategy to solve the partitioning problem without needing to retrain the model.
- **Resource Reduction:** 
    - UE Memory footprint reduced by **>33.6%**.
    - UE CPU footprint reduced by **>60%**.
- **Robustness:** Demonstrated effectiveness in heterogeneous network settings.

## Analysis & Relevance
Directly relevant to **Distributed Edge Inference**. The "UE-Edge-Core" split is a more realistic architectural model for 5G/6G networks than the traditional "Device-Server" split. The fact that it requires no retraining is a significant practical advantage for deploying existing large models on the edge.
