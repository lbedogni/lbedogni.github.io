# Communication-Efficient Multi-Modal Edge Inference via Uncertainty-Aware Distributed Learning

**Source:** [arXiv:2601.14942v1](https://arxiv.org/abs/2601.14942)
**Date:** Jan 2026
**Field:** Distributed Edge Inference, Multi-Modal Semantic Communication

## Summary
Proposes a three-stage framework to optimize the lifecycle of multi-modal edge inference, focusing on reducing communication overhead and increasing robustness against noisy inputs and fluctuating wireless channels.

## Core Innovations
1. **Three-Stage Framework**:
   - **Stage I (Local SSL)**: Devices perform multi-modal self-supervised learning locally to initialize encoders with zero device-server exchange.
   - **Stage II (Evidential Fusion)**: Distributed fine-tuning using evidential fusion to calibrate per-modality uncertainty and aggregate features reliably.
   - **Stage III (Uncertainty-Guided Feedback)**: An adaptive retransmission policy that requests additional features only for samples with high uncertainty, optimizing the communication-accuracy tradeoff.
2. **Information-Theoretic Guarantees**: Establishes how task-relevant information is preserved under channel constraints.

## Results
- **Efficiency**: Reaches target accuracy with 10x to 20x fewer training communication rounds compared to baseline methods.
- **Robustness**: Remains effective even when one modality is severely degraded.
- **Application**: Validated on RGB-depth indoor scene classification.

## Analysis for Luca
Directly relevant to **Distributed Edge Inference**. The emphasis on "zero-communication" initialization and uncertainty-guided adaptive communication provides a strong blueprint for reducing the bottleneck of wireless links in multi-modal systems.
