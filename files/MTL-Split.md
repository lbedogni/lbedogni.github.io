---
title: "MTL-Split: Multi-Task Learning for Edge Devices using Split Computing"
date: 2026-07-05
type: entity
source: "https://dl.acm.org/doi/abs/10.1145/3649329.3655686"
tags: [IoT, Edge Computing, Split Computing, Multi-Task Learning]
---

# MTL-Split

## Summary
MTL-Split focuses on resource-constrained embedded systems (e.g., automotive) where running multiple dedicated DNNs for different tasks is too computationally expensive.

The proposed architecture integrates **Split Computing (SC)** and **Multi-Task Learning (MTL)**:
- **Shared Backbone**: A single DNN backbone is deployed on the edge device.
- **Task-Specific Heads**: Different heads are deployed on remote servers.

## Key Results
- Minimizes data transmission and computational overhead.
- Enables the execution of multiple inference tasks using a single shared local model.

## Relevance to Luca
Directly relates to **Split Computing** and **Edge Computing**, demonstrating how to handle multi-objective inference tasks efficiently in distributed environments.
