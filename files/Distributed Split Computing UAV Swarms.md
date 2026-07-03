---
title: "Distributed Split Computing Using Diffusive Metrics for UAV Swarms"
date: 2025-03-16
type: paper
source: "https://arxiv.org/abs/2503.16146"
arxiv: "2503.16146"
tags: [Split Computing, UAV, Edge Computing, Distributed Inference, Diffusive Metrics, Early Exit]
---

# Distributed Split Computing Using Diffusive Metrics for UAV Swarms

## Key Info
- **Source:** [arXiv:2503.16146](https://arxiv.org/abs/2503.16146)
- **Publication:** Journal of Systems Architecture (Elsevier)
- **Date:** v3 updated April 8, 2026
- **Authors:** Talip Tolga Sarı, Gökhan Seçinti, Angelo Trotta

## Summary
This research presents a fully distributed approach to split computing specifically for **UAV swarms**, addressing the challenge of executing machine learning tasks in large-scale UAV swarms where network volatility and heterogeneous resources make centralized orchestration inefficient. The core innovation is the use of **diffusive metrics** to allow nodes in a swarm to iteratively determine the best way to partition and distribute inference tasks without relying on a central coordinator.

## Key Contributions
- **Aggregated Gigaflops**: A new iterative measure that allows each UAV to estimate its own and its neighbors' computing capacity without requiring global network knowledge
- **Intelligent Forwarding**: Partial inferences are forwarded to underutilized nodes based on the diffusive metric, improving throughput and reducing latency
- **Adaptive Inference**: Incorporates an **early-exit mechanism** to handle sudden workload surges and changing node conditions on-the-fly

## Analysis & Relevance
This is highly relevant to **Distributed Edge Inference** and **Split Computing**. Specifically:
- The shift from centralized to diffusive, distributed orchestration is a critical step for scalability in edge networks
- The application to UAV swarms provides a concrete use case for split computing in highly dynamic environments
- Addresses rapid changes in swarm topology and resource availability through decentralized decision-making

## Significance
Provides a blueprint for scalable, robust distributed intelligence in aerial networks, reducing communication bottlenecks by enabling fully distributed orchestration in mobile ad-hoc networks (MANETs).

#toread #IoT #EdgeComputing #DistributedInference #SplitComputing #UAVSwarms