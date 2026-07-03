# Towards Large Model Feature Coding
- **Date:** May 20, 2026
- **Authors:** Youwei Pang, Changsheng Gao, Dong Liu, Huchuan Lu, Weisi Lin
- **Source:** arXiv

## Summary
This paper introduces **LaMoFCBench**, a comprehensive feature dataset designed for large model feature coding across diverse tasks and scenarios. It focuses on optimizing the transmission of intermediate features in **split-computing** environments, exploring various split points and architectures to reduce communication overhead while maintaining performance.

## Analysis
The work addresses a critical bottleneck in split computing: the "feature explosion" where intermediate activations are too large to transmit efficiently. By creating a standardized benchmark, the authors enable a more systematic evaluation of feature coding techniques, which is essential for scaling distributed inference to larger, more complex models (like LLMs or large vision models) on edge devices.
