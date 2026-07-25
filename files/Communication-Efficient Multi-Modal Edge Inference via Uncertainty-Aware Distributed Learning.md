---
title: "Communication-Efficient Multi-Modal Edge Inference via Uncertainty-Aware Distributed Learning"
date: 2026-01-21
type: entity
source: "https://arxiv.org/abs/2601.14942"
tags: [edge-inference, multi-modal, semantic-communication, distributed-learning]
---

# Communication-Efficient Multi-Modal Edge Inference via Uncertainty-Aware Distributed Learning

## Summary
This paper addresses the communication overhead and robustness challenges in multi-modal edge inference (MMEI) over bandwidth-limited wireless links. The authors propose a three-stage communication-aware distributed learning framework to optimize the trade-off between communication and accuracy.

## Key Contributions
- **Three-Stage Framework**:
    1. **Local Self-Supervised Learning**: Devices learn modality-specific encoders locally to minimize initial device-server exchanges.
    2. **Centralized Evidential Fusion**: Distributed fine-tuning that uses evidential fusion to calibrate uncertainty and handle noise or channel fading.
    3. **Uncertainty-Guided Feedback**: A mechanism that selectively requests additional features only for uncertain samples.
- **Robustness**: The system remains effective even under modality degradation or significant channel variation.

## Results
- Higher accuracy compared to self-supervised and fully supervised baselines.
- Significant reduction in training communication rounds.
- Demonstrated efficiency on RGB-depth indoor scene classification.

## Analysis for Luca
Highly relevant to **Distributed Edge Inference**. The use of evidential fusion to handle uncertainty in wireless environments is a strong point for robust distributed systems.
