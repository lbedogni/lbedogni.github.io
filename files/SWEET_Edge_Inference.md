# SWEET: serving workload-balanced end-to-end efficient and tailored edge inference via quantization and partitioning

**Source**: Frontiers in Complex Systems ([Link](https://www.frontiersin.org/journals/complex-systems/articles/10.3389/fcpxs.2026.1801157/full))
**Date**: 2026

## Summary
SWEET is an accuracy-aware inference serving system that dynamically tailors the execution pattern for each request. It co-optimizes layer-wise model quantization and the device-server workload split based on the device's compute capacity, required accuracy, and current channel conditions.

## Key Contributions
- **Joint Optimization**: Integrates model quantization and inference partitioning into a single framework.
- **Accuracy-Awareness**: First system to use a theoretical measurement of accuracy degradation to optimize quantization bitwidths without violating user-defined accuracy requirements.
- **Efficiency**: Achieves >80% reduction in communication payload while keeping accuracy degradation below 1%.
- **Adaptability**: Handles heterogeneous devices (phones, watches, etc.) and time-varying network conditions.

## Analysis & Relevance
Extremely relevant to **Split Computing** and **Edge Inference**. The combination of quantization and partitioning is a powerful approach to reduce the "communication bottleneck" in split computing. The ability to provide request-specific patterns makes it highly flexible.
