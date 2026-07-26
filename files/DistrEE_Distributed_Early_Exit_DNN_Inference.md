# DistrEE: Distributed Early Exit of Deep Neural Network Inference on Edge Devices

**URL:** https://arxiv.org/html/2502.15735v1
**Date:** 2026 (Feb 2026)
**Tags:** #DistributedInference #EdgeIntelligence #EarlyExit #EdgeComputing

## Summary
DistrEE is a distributed DNN inference framework that combines multi-node collaborative inference with an early-exit mechanism. It allows the system to terminate the inference process early if a reliable prediction is reached, adapting to both the difficulty of the input data and the available resources of the edge devices.

## Key Contributions
- **Early Exit Integration:** Integrates model early exits within a distributed inference framework for multi-node scenarios.
- **Adaptive Policy:** Implements an early exit policy to control termination, balancing the trade-off between inference latency and accuracy.
- **Joint Training:** Proposes an end-to-end loss function for joint training of the distributed models and the exit branches.

## Analysis & Relevance
Directly aligns with "Distributed Edge Inference". The approach of using early exits to handle "input difficulty variability" is a sophisticated way to optimize edge resources, moving beyond simple model splitting or compression.
