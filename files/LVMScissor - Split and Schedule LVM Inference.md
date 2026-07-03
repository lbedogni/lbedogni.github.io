---
title: "LVMScissor: Split and Schedule Large Vision Model Inference on Mobile Edges via Salp Swarm Algorithm"
date: 2026-06-27
type: entity
source: "https://ieeexplore.ieee.org/document/10923690"
tags: [Split-Computing, Distributed-Inference, LVM, ViT, Salp-Swarm-Algorithm]
---

# LVMScissor: Split and Schedule LVM Inference

## Summary
LVMScissor addresses the challenge of performing split inference for Large Vision Models (LVMs), specifically those based on Vision Transformers (ViT), on resource-constrained mobile edges. The main hurdle is the massive size of intermediate results produced by LVMs, which often makes traditional split inference inefficient due to bandwidth limitations.

## Key Approach
- **Model Parallelism**: Leverages parallelism to distribute the workload.
- **Meta-heuristic Optimization**: Uses the **Salp Swarm Algorithm** to optimize the split strategy and the scheduling of model parallelism.

## Results
Evaluation results indicate that LVMScissor is faster than current state-of-the-art inference acceleration approaches for LVMs on the edge.

## Analysis
By optimizing where the model is "cut" and how the resulting pieces are scheduled, LVMScissor makes it feasible to deploy high-capacity vision models on mobile devices without being crippled by the communication overhead of intermediate tensors.
