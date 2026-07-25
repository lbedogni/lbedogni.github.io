---
title: "Why Should the Server Do It All?: A Scalable, Versatile, and Model-Agnostic Framework for Server-Light DNN Inference over Massively Distributed Clients via Training-Free Intermediate Feature Compression"
date: 2025-11-03
type: entity
source: "https://arxiv.org/abs/2511.11608"
tags: [SplitComputing, FeatureCompression, DNN, ServerLight]
---

# Why Should the Server Do It All? (SLICER)

## Summary
SLICER is a plug-and-play framework for retraining-free intermediate feature compression in split computing, designed to reduce both communication overhead and server load.

## Key Findings
- **Components**:
  1. **Asymmetric Top-K Filtering (ATKF)**: Sparsifies low-magnitude activations.
  2. **Magnitude-Splitting (MS)**: Groups non-zeros into equal blocks.
  3. **Adaptive Bit Quantization (ABQ)**: Selects per-block bitwidths.
- **Results**: Reduces uplink volume by **10x** and server GPU time by **4.4x**.
- **Generalization**: Keeps task quality within 0-3 percentage points of the baseline across Vision and LLM workloads.

## Analysis
SLICER tackles the "bulky intermediate features" problem in split computing. By shifting the burden of compression and some meaningful compute to the edge, it creates a "server-light" architecture, which is a primary goal of scalable distributed inference.
