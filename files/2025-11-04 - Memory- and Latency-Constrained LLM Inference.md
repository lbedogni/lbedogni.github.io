---
title: "Memory- and Latency-Constrained Inference of Large Language Models via Adaptive Split Computing"
date: 2025-11-04
type: source
source: "https://arxiv.org/abs/2511.04002"
tags: [SplitComputing, LLM, EdgeComputing, IoT, Quantization, DistributedInference]
---

# Memory- and Latency-Constrained Inference of Large Language Models via Adaptive Split Computing

**Link:** [arXiv:2511.04002](https://arxiv.org/abs/2511.04002)
**Date:** 2025-11-04

## Summary
This paper introduces the first **autoregressive-aware split computing framework** designed specifically for deploying Large Language Models (LLMs) on resource-constrained IoT/edge devices. It addresses the specific challenges of LLMs, such as massive parameter footprints and the expanding Key-Value (KV) cache during iterative token generation.

## Key Contributions
- **One-Point Split Compression (OPSC):** A mixed-precision quantization scheme that partitions the model into front-end and back-end segments with different precision levels to prevent Out-Of-Memory (OOM) failures.
- **Intermediate Compression Pipeline:** Uses a combination of **Threshold Splitting (TS)** and **Token-wise Adaptive Bit Quantization (TAB-Q)** to dramatically reduce communication overhead between the edge device and the server while preserving accuracy-critical activations.
- **Unified Optimization Framework:** A joint optimization of split points, quantization settings, and sequence lengths to satisfy strict memory and latency constraints.

## Analysis of Results
- **Performance:** Achieves a **1.49x inference speedup**.
- **Efficiency:** Significant reduction in communication overhead.
- **Comparison:** Outperforms or remains competitive with state-of-the-art quantization methods like **SmoothQuant**, **OmniQuant**, and **Atom** in terms of accuracy.

## Relevance to Luca
This work is highly relevant as it bridges the gap between **Split Computing** and **LLM deployment**. It specifically targets the bottlenecks of distributed edge inference (latency and memory) and proposes a sophisticated quantization-aware splitting strategy that is directly applicable to Distributed Edge Inference and Split Computing research.
