---
title: "Serving Mixture-of-Expert Models with Seamless Runtime Parallelism Switch"
date: 2026-06-29
type: summary
source: "https://arxiv.org/abs/2606.26607"
tags: [Distributed Inference, MoE, Parallelism, LLM Serving, Edge Computing]
---

# Serving Mixture-of-Expert Models with Seamless Runtime Parallelism Switch

## Summary
The paper presents **Moebius**, a serving system for Mixture-of-Experts (MoE) models that can switch between **Expert Parallelism (EP)** and **Tensor Parallelism (TP)** at runtime without needing to restart the engine or drop in-flight requests.

The core insight is that EP and TP are simply different layouts of the same model. Moebius uses high-bandwidth GPU interconnects to reshard expert weights and the KV cache between these layouts in real-time (completing switches in 215-434 ms).

## Results & Analysis
- **Performance**: Moebius matches the performance of the optimal static parallelism (either TP or EP) across all concurrency levels.
- **RL Rollouts**: Specifically improved performance on RL rollouts by 1.16-1.25x.
- **Overhead**: Maintains both layouts resident with only a 2.4% memory overhead.
- **Significance**: This is a major step toward "elastic" distributed inference. For edge clusters, the ability to adapt the parallelism strategy to the current request volume allows for optimal latency and throughput without the rigid constraints of a single chosen deployment strategy.
