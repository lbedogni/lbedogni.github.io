---
title: "DistrEE: Distributed Early Exit of Deep Neural Network Inference on Edge Devices"
date: 2026-07-14
type: entity
source: "https://arxiv.org/abs/2502.15735"
tags: [IoT, Edge Computing, Distributed Inference, Early Exit, DNN]
---

# DistrEE: Distributed Early Exit of Deep Neural Network Inference on Edge Devices

## Summary
DistrEE is a distributed DNN inference framework designed for multi-node collaborative edge scenarios. It addresses the inefficiency of applying the same computational effort to all inputs regardless of their complexity or the current state of edge resources.

## Key Concepts
- **Collaborative Inference**: Leverages multiple edge devices to perform resource-hungry inference tasks.
- **Network of Neural Networks (NoNN)**: A distribution approach where a teacher model is partitioned into multiple independent student models via knowledge distillation.
- **Early Exit**: Integrates side-branches in the DNN that allow the model to exit inference early if a reliable prediction is reached, saving computation and reducing latency.

## Analysis
The framework effectively strikes a balance between **latency and accuracy**. By adapting the inference depth to the "difficulty" of the input data, DistrEE minimizes resource wastage on simple samples while still providing high accuracy for complex ones. This is particularly critical in IoT environments where power and compute are strictly limited.

## Reference
- Source: [[https://arxiv.org/abs/2502.15735]]
