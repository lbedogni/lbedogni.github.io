---
title: "DistrEE: Distributed Early Exit of Deep Neural Network Inference on Edge Devices"
date: 2026-06-30
type: entity
source: "https://arxiv.org/abs/2502.15735"
tags: [distributed-inference, edge-computing, early-exit, dnn, iot]
---

# DistrEE: Distributed Early Exit of Deep Neural Network Inference on Edge Devices

## Overview
DistrEE is a distributed DNN inference framework designed to optimize the trade-off between inference latency and accuracy in edge computing environments. It specifically addresses the inefficiency of applying the same computational effort to both simple and complex input data in multi-node collaborative scenarios.

## Key Concepts
- **Distributed Inference (NoNN)**: Based on the Network of Neural Networks paradigm, where a teacher model is distilled into multiple independent student models deployed across edge devices.
- **Early Exit Mechanism**: Introduces side branches (exit points) at intermediate layers of the DNN. If a prediction at an early stage meets a certain confidence threshold (e.g., low entropy), the process terminates early, saving computational resources.
- **Adaptive Inference**: By combining these two, DistrEE can adapt to both the **input difficulty** (simple vs. complex images) and **resource fluctuations** on the edge nodes.

## Contributions
1. **Framework Integration**: First to integrate early exit mechanisms with multi-node collaborative inference (NoNN).
2. **Joint Training**: Proposed an end-to-end loss function to jointly train the multi-branch student models and the early exit points, ensuring each branch is an effective predictor.
3. **Performance**: Demonstrated significant improvements in the latency-accuracy trade-off compared to static distributed inference.

## Analysis & Relevance
This paper is highly relevant to Luca's work on **Distributed Edge Inference** and **Split Computing**. While traditional split computing often partitions a model linearly (layer-by-layer), DistrEE's approach of using distilled independent students with early exits provides a more flexible and resilient way to handle heterogeneous edge clusters and variable workloads.
