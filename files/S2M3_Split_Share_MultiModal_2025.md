# S2M3: Split-and-Share Multi-Modal Models for Distributed Multi-Task Inference on the Edge

**Date:** March 2025
**Source:** IEEE ICDCS 2025 / Cyberinitiative
**Topics:** #SplitComputing #MultiModal #DistributedInference #EdgeComputing

## Summary
Introduces **S2M3**, a "split-and-share" architecture designed to support multiple multi-modal tasks on resource-constrained edge devices by reusing common functional modules.

## Key Contributions & Analysis
- **Functional-Level Splitting:** Instead of splitting at arbitrary layers, S2M3 splits multi-modal models at the module level (e.g., encoders, decoders).
- **Module Sharing:** Identifies and shares common modules across different tasks to significantly reduce memory footprint (up to 62% reduction in multi-task settings).
- **Greedy Module Placement:** Implements a placement strategy with per-request parallel routing, prioritizing compute-intensive modules to optimize data flow.
- **Performance:** Reduces inference latency by up to 56.9% compared to cloud-based AI without losing accuracy.

## Relevance to Research
A strong example of "Split Computing" applied to multi-modal AI, showing how modularity can be exploited for efficiency in distributed edge environments.
