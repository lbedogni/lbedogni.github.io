---
title: "Hierarchical Auction-assisted Learning for Offloading in SAGIN"
date: 2026-06-29
type: summary
source: "https://arxiv.org/abs/2606.26293"
tags: [IoT, Edge Computing, Distributed Inference, SAGIN, Task Offloading]
---

# Hierarchical Auction-assisted Learning for Offloading in SAGIN

## Summary
This paper introduces **HALO**, a hierarchical auction-assisted learning framework designed for delay-aware task offloading and resource scheduling within a three-tier Space-Air-Ground Integrated Network (SAGIN). The network comprises IoT devices, UAV edge nodes, and a High-Altitude Platform Station (HAPS). 

The authors formulate the joint task association and resource control (bandwidth, transmit power, and CPU frequency) as a non-convex mixed-integer nonlinear programming (MINLP) problem. To solve this, HALO employs:
1. **Auction-based Task Association**: To handle the discrete problem of assigning tasks to nodes.
2. **Hierarchical Proximal Policy Optimization (HPPO)**: To optimize the continuous resource allocation parameters.

## Results & Analysis
- **Performance**: HALO consistently outperforms traditional DRL baselines (PPO, DDPG, SAC).
- **Key Metric**: Achieved an average improvement of 8.7 percentage points in task success rate over PPO.
- **Robustness**: Demonstrated significantly higher robustness under varying traffic loads compared to DDPG and SAC.
- **Significance**: The macro-micro slot model allows for a more granular tracking of transmission and computation progress, which is crucial for delay-sensitive applications in complex heterogeneous edge environments.
