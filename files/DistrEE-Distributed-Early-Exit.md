# DistrEE: Distributed Early Exit of Deep Neural Network Inference on Edge Devices

**Source:** [arXiv:2502.15735](https://arxiv.org/abs/2502.15735)
**Date:** Feb 2025

## Summary
DistrEE is a distributed DNN inference framework that integrates "early exit" mechanisms into multi-node collaborative inferencing. It allows a model to terminate its inference process early if specific quality of service (QoS) requirements are met, reducing unnecessary computation.

## Key Contributions
- **Early Exit + Distributed Inference:** The first framework to merge early exit strategies with distributed multi-node collaborative inference.
- **Early Exit Policy:** A control mechanism to determine the optimal point of termination during the inference process.
- **QoS-Driven:** Specifically designed to balance the trade-off between inference latency and accuracy.

## Analysis & Relevance
This is highly relevant to **Edge Computing** and **Distributed Inference**. By allowing early exits in a distributed setting, DistrEE optimizes the use of limited edge resources. It complements the concept of split computing by adding a dynamic termination layer based on the complexity of the input data and available resources.

## Status
- [ ] Read full paper
- [ ] Inspect the early exit policy logic
- [ ] Compare with standard DNN partitioning strategies
