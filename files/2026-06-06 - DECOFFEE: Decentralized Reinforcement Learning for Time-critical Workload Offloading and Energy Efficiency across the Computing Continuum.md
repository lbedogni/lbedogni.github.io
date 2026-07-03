---
type: paper
tags: [iot, time-critical, reinforcement-learning, edge-computing, workload-offloading, computing-continuum]
url: https://arxiv.org/abs/2604.24507
date_added: 2026-06-06
---

# DECOFFEE: Decentralized Reinforcement Learning for Time-critical Workload Offloading and Energy Efficiency across the Computing Continuum

## Summary
DECOFFEE is a decentralized reinforcement learning framework designed to optimize workload placement across the Edge-Cloud computing continuum for latency-sensitive and battery-constrained IoT applications. It enables far-edge nodes to dynamically decide whether to process tasks locally or offload them to neighbors or the cloud, balancing execution delay, energy consumption, and strict timeout constraints. The system uses a Double Dueling Deep Q-Network (DQN) enhanced with LSTM forecasting to handle stochastic arrivals and time-varying network conditions.

## Key Takeaways
- **Decentralized Architecture:** Each edge agent acts as an autonomous learning entity, reducing the need for a central orchestrator and improving scalability.
- **Hybrid Model:** Combines Double Dueling DQN for policy optimization with LSTM for predicting future load and network conditions.
- **Multi-Objective Optimization:** Jointly optimizes for system delay, energy efficiency, and workload drop rate.
- **Computing Continuum:** Operates across far-edge, neighboring edge nodes, and the cloud to ensure time-critical constraints are met.

## Relevance
This paper is directly relevant to Prof. Bedogni's research in **IoT for time-critical systems** and **split computing**. Specifically, it addresses the challenge of maintaining low latency (critical for glass-to-glass latency) by dynamically offloading workloads across the computing continuum—a core concept of **fluid computing**. The use of RL to manage time-critical timeouts in a distributed IoT environment provides a technical roadmap for implementing adaptive split-computing strategies.

## Links
- [PDF](https://arxiv.org/pdf/2604.24507)
- [Publication Page](https://arxiv.org/abs/2604.24507)
