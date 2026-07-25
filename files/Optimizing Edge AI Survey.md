---
title: "Optimizing Edge AI: A Comprehensive Survey on Data, Model, and System Strategies"
date: 2025-01-03
type: entity
source: "https://arxiv.org/html/2501.03265v1"
tags: [EdgeAI, ModelOptimization, SystemDesign, IoT]
---

# Optimizing Edge AI: A Comprehensive Survey on Data, Model, and System Strategies

## Summary
This paper proposes an "Optimization Triad" for deploying AI models on resource-constrained edge devices, focusing on three layers: Data, Model, and System.

### The Optimization Triad
- **Data Optimization**: Cleaning, compression, and augmentation to improve training quality and reduce footprint.
- **Model Optimization**: Pruning, quantization, and knowledge distillation to reduce parameter count and computation.
- **System Optimization**: Framework support and hardware acceleration to optimize the execution pipeline.

## Analysis
This survey provides a pragmatic framework for implementing **Split Computing**. In a split-computing scenario, the "Model" optimization layer is used to determine where to cut the network (splitting point) to balance computation and communication costs. The "System" layer is crucial for ensuring that the split-inference process doesn't introduce more latency via network overhead than it saves via computation offloading. The "Data" layer is relevant for optimizing the intermediate tensors sent between the split parts of the model.
