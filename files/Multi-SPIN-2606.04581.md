# Multi-SPIN: Multi-Access Speculative Inference for Cooperative Token Generation at the Edge

**arXiv ID:** 2606.04581
**Date:** June 2026
**Authors:** Haotian Zheng, Zhanwei Wang, Mingyao Cui, Chang Cai, Hongyang Du, Kaibin Huang
**Tags:** #EdgeComputing #DistributedInference #SplitComputing #LLM #SpeculativeInference

## Summary
This paper introduces **Multi-SPIN**, a distributed architecture for speculative inference in multiuser edge systems. It aims to accelerate Large Language Model (LLM) token generation by distributing the workload between resource-constrained edge devices and a central edge server.

### Key Mechanism
- **On-Device (Edge):** Small Language Models (SLMs) generate candidate "draft" tokens.
- **Server (Edge Server):** A larger LLM verifies these drafts in parallel batches.
- **Cooperation:** The system effectively splits the inference process, leveraging the low latency of local SLMs and the high accuracy/power of the server LLM.

### Main Contributions
- **Multi-Access Draft Control:** The authors propose a joint optimization of **draft length** and **bandwidth allocation** to maximize the "sum token goodput" (the total number of correctly generated tokens per unit time).
- **Handling Heterogeneity:** The framework accounts for the diverse computational and communication capabilities of different user devices.
- **Optimization:** They derive closed-form algorithms for draft control in both homogeneous (same draft length for all) and heterogeneous (varying draft lengths) scenarios.

## Analysis & Results
- **Performance:** Multi-SPIN improves token goodput by up to **88%** compared to baselines that ignore device heterogeneity.
- **Insights:** In homogeneous cases, bandwidth allocation must compensate for weaker devices to avoid synchronization bottlenecks. In heterogeneous cases, rewarding users with higher acceptance rates further enhances performance.
- **Relevance to Luca's Field:** This is a prime example of **Distributed Edge Inference** and **Split Computing**, demonstrating how to optimize the split point (drafting vs. verification) and resource allocation in a real-world edge deployment.

## Link
[arXiv:2606.04581](https://arxiv.org/abs/2606.04581)
