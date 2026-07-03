---
title: "AVERY: Intent-Driven Adaptive VLM Split Computing via Embodied Self-Awareness for Efficient Disaster Response Systems"
date: 2025-11-01
type: paper
source: "https://arxiv.org/abs/2511.18151"
arxiv: "2511.18151"
tags: [Split Computing, VLM, Edge Intelligence, UAV, Disaster Response, Intent-driven, Adaptive Inference]
---

# AVERY: Intent-Driven Adaptive VLM Split Computing via Embodied Self-Awareness for Efficient Disaster Response Systems

## Key Info
- **arXiv:** [2511.18151](https://arxiv.org/abs/2511.18151)
- **Date:** November 2025 (v3 updated March 2026)
- **Model used:** LISA-7B

## Summary
AVERY is an intent-driven adaptive split computing framework designed for deploying Vision-Language Models (VLMs) on resource-constrained platforms (specifically UAVs) for disaster response. Recognizing that different mission objectives (e.g., situational monitoring vs. detailed investigation) require different resource allocations and semantic outputs, AVERY introduces a functional dual-stream split:

### Functional Dual-Stream Architecture
1. **Context Stream**: High-frequency, low-resolution for real-time awareness
2. **Insight Stream**: Low-frequency, high-fidelity for deep analysis

The framework employs a hierarchical split strategy (functional then depth-wise) and an onboard controller that adjusts compression models based on network conditions and operator intent to dynamically partition the Insight stream between edge and cloud.

## Key Results
- **Accuracy:** 11.2% higher accuracy than raw image compression
- **Energy:** **93.98% lower energy consumption** compared to full-edge execution
- **Stability:** Average accuracy remained within **0.75%** of the static High-Accuracy baseline during dynamic network fluctuations

## Analysis & Relevance
Highly relevant for **Distributed Edge Inference** and **Split Computing**, especially:
- The application of VLMs to mobile edge platforms
- The concept of "intent-driven" adaptation
- Hierarchical splitting (functional + depth-wise) as opposed to simple depth-wise partitioning
- Makes high-level semantic reasoning (VLMs) feasible on constrained edge devices

## Significance
This paper advances split computing by moving beyond simple depth-wise partitioning to a cognitive-inspired functional split, making high-level semantic reasoning (VLMs) feasible on the edge.

#toread #edge-computing #split-computing #vlm #uav #disaster-response