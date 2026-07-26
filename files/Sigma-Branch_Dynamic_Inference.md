# Sigma-Branch: Hierarchical Single-Path Network Reconstruction for Dynamic Inference with Reduced Active Parameters

**Date Found:** 2026-06-24
**Source:** arXiv (Submitted 2026-06-07)
**Category:** Edge AI / Dynamic Inference

## Summary
The paper introduces "Sigma-Branch", which targets the memory bottleneck of deploying deep neural networks on edge accelerators. It uses a hierarchical single-path network reconstruction method to reduce the number of active parameters during dynamic inference.

## Key Contributions
- **Hierarchical Single-Path Reconstruction:** A way to dynamically adjust the network path to minimize memory usage.
- **Reduced Active Parameters:** Directly addresses the memory-constrained nature of edge accelerators.
- **Dynamic Inference:** Allows the model to adapt its computation based on the input or available resources.

## Analysis
Relevant to **Edge Computing** and **Split Computing** concepts, specifically in how to optimize the model footprint and execution path on the device side. It aligns with the goal of making high-performance inference feasible on low-power edge hardware.

## Status
- [ ] Read full paper
- [ ] Check the "single-path" mechanism
- [ ] Compare with existing pruning/quantization methods
