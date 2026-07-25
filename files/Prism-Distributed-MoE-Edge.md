---
title: "Prism: Accelerating Edge Inference for Distributed MoE Models with Latency-Optimized Expert Placement"
date: 2026-07-06
type: entity
source: "https://arxiv.org/abs/2508.12851"
tags: [IoT, Edge Computing, Distributed Inference, MoE, LLM]
---

# Prism

## Summary
Prism is a collaborative inference framework designed for Mixture-of-Experts (MoE) models deployed across heterogeneous, GPU-equipped edge servers. It addresses the massive memory footprint of MoE models (e.g., Mixtral-8x7B) which exceeds the capacity of single edge GPUs.

Prism leverages the **intrinsic sparsity** and **input locality** of MoE workloads to minimize inter-server communication. It uses a **Global Scheduler** to manage expert placement based on activation frequencies and resource constraints.

Key components include:
- **Activation-aware Expert Placement**: Allocates experts to servers based on how frequently they are used for local requests, maximizing local execution.
- **Runtime Expert Migration**: A lightweight mechanism to adapt the distribution of experts as workload patterns evolve over time.

## Key Results
- Reduces inference latency by up to **30.6%**.
- Significantly lowers cross-server communication costs compared to state-of-the-art baselines.
- Effectively handles hardware heterogeneity (varying GPU memory and compute) and dynamic workload shifts.

## Relevance to Luca
Directly relevant to **Distributed Edge Inference** and **Split Computing**. Prism's approach to "expert placement" is essentially a specialized form of model partitioning and placement for sparse models, providing a blueprint for scaling large-capacity models on limited edge resources.
