---
title: "Intent-Driven Adaptive VLM Split Computing via Embodied Self-Awareness for Efficient Disaster Response Systems"
date: 2025-11-22
type: entity
source: "https://arxiv.org/abs/2511.18151"
tags: [VLM, split-computing, UAV, disaster-response, adaptive-inference]
---

# Intent-Driven Adaptive VLM Split Computing via Embodied Self-Awareness for Efficient Disaster Response Systems

## Summary
The authors present **AVERY**, a split computing framework for deploying Vision-Language Models (VLMs) on resource-constrained UAVs in disaster zones, where network bandwidth is unstable and latency is critical.

## Key Contributions
- **Cognitive Dual-Stream Split**:
    - **Context Stream**: High-frequency, low-resolution for real-time awareness.
    - **Insight Stream**: Low-frequency, high-fidelity for deep semantic analysis.
- **Hierarchical Splitting**: Computation is first separated by function (Context vs. Insight), then depth-wise partitioned across edge and cloud.
- **Self-Aware Controller**: An onboard controller monitors operator intent and network conditions to select the optimal compression model at runtime.

## Results
- 11.2% higher accuracy than raw image compression.
- 93.98% lower energy consumption than full-edge execution.
- Maintains accuracy within 0.75% of a static high-accuracy baseline during dynamic adaptation.

## Analysis for Luca
Excellent example of **Split Computing** and **Edge Computing** applied to VLMs. The distinction between "Context" and "Insight" streams is a novel approach to intent-driven resource allocation.
