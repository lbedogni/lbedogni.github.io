---
title: "Distributed Split Computing Using Diffusive Metrics for UAV Swarms"
date: 2025-03-20
type: entity
source: "https://arxiv.org/abs/2503.16146"
tags: [Distributed Split Computing, UAV Swarms, Diffusive Metrics]
---

# Distributed Split Computing Using Diffusive Metrics for UAV Swarms

## Summary
This paper proposes a fully distributed, diffusive metric-based approach for split computing in large-scale UAV swarms to overcome the bottlenecks of centralized orchestration.

## Key Analysis
- **Problem:** Centralized partitioning fails in large swarms due to communication bottlenecks, latency, and rapid topology changes.
- **Solution:**
    - **Aggregated Gigaflops:** A new iterative measure that captures a node's own computing capacity and that of its neighbors without requiring global network knowledge.
    - **Intelligent Forwarding:** Partial inferences are forwarded to underutilized nodes based on these diffusive metrics.
    - **Early-Exit Mechanism:** Adapts the inference pathway on-the-fly to handle workload surges or changing node conditions.
- **Results:** Significantly outperforms baseline strategies in latency, fairness, and energy consumption.
- **Significance:** Demonstrates a scalable blueprint for deploying robust distributed intelligence in aerial networks without a central controller.
