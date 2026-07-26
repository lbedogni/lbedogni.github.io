# Memory- and Latency-Constrained Inference of Large Language Models via Adaptive Split Computing

**Source**: [arXiv:2511.04002v1](https://arxiv.org/abs/2511.04002v1)
**Date**: Nov 2025
**Field**: Split Computing, LLM, IoT

## Summary
This paper addresses the challenge of deploying Large Language Models (LLMs) on resource-constrained IoT devices. It identifies that standard split computing fails to account for the specific needs of autoregressive inference (iterative token generation and KV cache expansion).

## Key Contributions
- **One-Point Split Compression (OPSC)**: A mixed-precision quantization scheme that partitions the model into front-end and back-end segments to prevent Out-of-Memory (OOM) failures.
- **Two-Stage Intermediate Compression**: 
    - **Threshold Splitting (TS)**: Preserves accuracy-critical activations.
    - **Token-wise Adaptive Bit Quantization (TAB-Q)**: Dramatically reduces communication overhead.
- **Unified Optimization Framework**: Jointly optimizes split points, quantization settings, and sequence lengths to meet memory and latency constraints.

## Analysis & Results
- Achieved a **1.49x inference speedup**.
- Significantly reduced communication overhead.
- Outperformed state-of-the-art quantization methods like SmoothQuant and OmniQuant while maintaining or improving accuracy.
- Highly relevant for Luca's interest in **Distributed Edge Inference** and **Split Computing** for LLMs.
