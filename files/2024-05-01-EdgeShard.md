---
title: "EdgeShard: Efficient LLM Inference via Collaborative Edge Computing"
date: 2024-05-01
type: summary
source: "https://arxiv.org/abs/2405.14371"
tags: [LLM, EdgeComputing, CollaborativeComputing, DistributedInference]
---

# EdgeShard: Efficient LLM Inference via Collaborative Edge Computing

## Summary
EdgeShard is a general framework designed to enable the efficient inference of Large Language Models (LLMs) by leveraging **Collaborative Edge Computing (CEC)**. Instead of relying solely on cloud-edge vertical collaboration, it enables horizontal collaboration among heterogeneous edge devices.

## Key Concepts
- **Model Sharding**: The LLM is partitioned into "shards" and distributed across a set of selected edge devices and cloud servers based on their memory and computation capabilities.
- **Adaptive Optimization**: The framework uses a dynamic programming algorithm to jointly optimize device selection and model partitioning, aiming to either minimize inference latency or maximize throughput.
- **Collaborative Inference**: Supports both sequential inference (for single users) and pipeline parallel inference (to maximize resource utilization across the device pool).

## Results & Analysis
- **Performance**: Experiments with Llama2 models show up to a **50% reduction in latency** and a **2x improvement in throughput** compared to on-device or traditional vertical cloud-edge collaboration.
- **Relevance**: A high-impact application of Distributed Edge Inference for modern LLMs, solving the memory bottleneck by treating a local cluster of devices as a single distributed resource.
