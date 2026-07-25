---
title: "DAPO: Mobility-Aware Joint Optimization of Model Partitioning and Task Offloading for LLM Deployment at the Edge"
date: 2025-01-01
type: entity
source: "https://www.mdpi.com/2079-9292/14/19/3929"
tags: [LLM, Edge Computing, Model Partitioning, Mobility, Task Offloading]
---

# DAPO: Mobility-Aware LLM Edge Deployment

## Summary
The DAPO (Dynamic Adaptive Partitioning and Offloading) framework addresses the specific challenges of deploying Large Language Models (LLMs) in edge environments, where high computational demands conflict with limited device resources and the dynamic nature of user mobility.

## Key Contributions
- **Joint Optimization**: Simultaneously optimizes where the model is partitioned and where tasks are offloaded.
- **Mobility Awareness**: Incorporates user movement into the decision-making process to prevent inference interruption and optimize handover between edge nodes.
- **LLM Focus**: Specifically tailored for the memory and compute profiles of LLMs, which differ significantly from smaller CNNs or RNNs.

## Analysis
Extremely relevant given the current trend of **Edge LLMs**. The "Mobility-Aware" aspect is crucial for real-world IoT deployments where the client (e.g., a smartphone or robot) is moving between different edge access points.
