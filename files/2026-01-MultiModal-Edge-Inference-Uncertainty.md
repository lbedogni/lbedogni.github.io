# Communication-Efficient Multi-Modal Edge Inference via Uncertainty-Aware Distributed Learning

**Source:** [arXiv:2601.14942](https://arxiv.org/abs/2601.14942)
**Date:** Jan 2026 (Presented at MeditCom 2025)
**Field:** Multi-Modal Edge Inference, Semantic Communication, Distributed Learning

## Summary
The paper introduces a three-stage communication-aware distributed learning framework for multi-modal edge inference (MMEI). It aims to reduce the massive communication overhead typically required for training distributed encoders over bandwidth-limited wireless links while improving robustness against noisy inputs and channel fading.

## Key Analysis
- **Three-Stage Framework:**
    1. **Stage I (Local Pre-training):** Devices perform self-supervised learning locally to obtain modality-specific encoders with *zero* device-server communication.
    2. **Stage II (Evidential Fusion):** Uses centralized evidential fusion to calibrate per-modality uncertainty, making the system robust to corrupted or missing features.
    3. **Stage III (Uncertainty-Guided Feedback):** An adaptive mechanism that requests additional feature transmissions only for samples where the server's uncertainty exceeds a specific threshold.
- **Results:** The framework reduces training communication rounds by 10x to 20x compared to traditional methods and maintains high accuracy even when specific modalities (e.g., RGB or Depth) are severely degraded.

## Relevance to Luca's Research
Highly relevant to **IoT, Distributed Edge Inference, and Split Computing**. It tackles the critical trade-off between communication cost and inference accuracy in multi-modal systems, utilizing semantic communication to optimize the data flow between the edge and the server.
