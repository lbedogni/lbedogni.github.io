---
title: "AVERY: Intent-Driven Adaptive VLM Split Computing via Embodied Self-Awareness for Efficient Disaster Response Systems"
date: 2025-11-22
type: entity
source: "https://arxiv.org/abs/2511.18151"
tags: [Split Computing, VLM, UAV, Disaster Response]
---

# AVERY: Intent-Driven Adaptive VLM Split Computing via Embodied Self-Awareness for Efficient Disaster Response Systems

## Summary
AVERY is an intent-driven adaptive split computing framework for deploying Vision-Language Models (VLMs) on resource-constrained UAVs, specifically for disaster response scenarios.

## Key Analysis
- **Problem:** On-device VLMs are too heavy, and naive cloud offloading is unreliable in disaster zones with unstable bandwidth.
- **Solution:**
    - **Dual-Stream Split:** 
        - *Context Stream:* High-frequency, low-resolution for real-time awareness.
        - *Insight Stream:* Low-frequency, high-fidelity for deep semantic analysis.
    - **Hierarchical Splitting:** Computation is first separated by function, then partitioned depth-wise between edge and cloud.
    - **Self-Aware Controller:** Monitors network conditions and operator intent to adaptively select pre-trained compression models.
- **Results:** 11.2% higher accuracy than raw image compression, 93.98% lower energy consumption than full-edge execution, and maintains accuracy within 0.75% of the high-accuracy baseline.
- **Significance:** Enables real-time, queryable intelligence on UAVs by treating operator intent as a first-class system objective.
