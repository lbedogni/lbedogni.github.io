# Multi-Turn Distributed Inference with Mixture of Experts for 6G Edge--Cloud Networks

**Authors:** Bo Liu, Haiyuan Li, Yuelin Liu, Yulei Wu, Rasheed Hussain, Shadi Moazzeni, Dimitra Simeonidou
**Date:** Submitted 6 May, 2026 (Announced July 2026)
**Source:** arXiv

## Summary
This paper explores the deployment of Mixture-of-Experts (MoE) architectures across 6G edge-cloud networks. MoE models are used to reduce the computational and communication overhead of inference by activating only a sparse subset of the model's parameters (the "experts") for any given input. The authors propose a multi-turn distributed inference mechanism that optimizes the placement and activation of these experts across the edge and cloud to balance latency and accuracy.

## Analysis
This work is highly relevant to **Distributed Edge Inference** and **Edge Computing**. By leveraging MoE, it addresses the bandwidth bottlenecks of 6G networks, which is a core challenge in scaling large-scale AI models to the edge. The "multi-turn" aspect suggests a dynamic interaction between the edge and cloud, which aligns with the goal of creating more flexible, distributed inference pipelines.

**Key Takeaways for Luca:**
- Optimization of MoE for distributed environments.
- Bandwidth reduction strategies for 6G networks.
- Dynamic edge-cloud partitioning for sparse models.
