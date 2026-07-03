# [2502.15735] Distributed Early Exit of Deep Neural Network Inference on Edge Devices

**URL:** https://arxiv.org/abs/2502.15735
**Date:** February 2025
**Authors:** Xin Wu

## Summary
Introduces **DistrEE**, a framework for distributed DNN inference that integrates "early exit" mechanisms with multi-node collaborative inferencing. It aims to meet specific Quality of Service (QoS) requirements by terminating inference early when acceptable accuracy is reached.

## Key Analysis
- **Innovation:** Combines early-exit (which usually happens on a single device) with distributed inference (splitting tasks across nodes).
- **Trade-off:** Provides a dynamic policy to balance inference latency and accuracy based on available resources and input complexity.
- **Impact:** Enables resource-hungry tasks on edge devices by leveraging collaboration and adaptive computation.

## Relevance to Luca
Highly relevant to **Distributed Edge Inference** and **Split Computing**. It specifically addresses the challenge of fluctuating edge resources and varying input difficulty.
# DistrEE: Distributed Early Exit of Deep Neural Network Inference on Edge Devices

**Source:** [arXiv:2502.15735](https://arxiv.org/abs/2502.15735)
**Date:** February 2025
**Field:** Distributed Edge Inference, Model Compression/Optimization

## Summary
**DistrEE** is a distributed DNN inference framework that combines **model early exit** with **distributed inference** for multi-node collaborative scenarios. It aims to meet specific Quality of Service (QoS) requirements by terminating the inference process early when a sufficient confidence level is reached.

## Key Contributions
- **Integrated Early Exit:** Merges the concept of early-exit DNNs (which allow a model to stop processing if the result is clear) with distributed execution across multiple edge nodes.
- **Exit Policy:** Designs a specific policy to determine the optimal termination point for the inference task.

## Results & Analysis
- **Trade-off:** Successfully achieves an effective trade-off between **inference latency** and **accuracy**.
- **Efficiency:** Reduces the computational burden on the edge network by avoiding unnecessary layers of processing for "easy" inputs.

## Relevance to Luca's Research
Relevant to **Distributed Edge Inference**. The integration of early exit mechanisms into distributed frameworks can significantly reduce the communication overhead and energy consumption in edge clusters, which is a core concern in **Edge Computing**.
