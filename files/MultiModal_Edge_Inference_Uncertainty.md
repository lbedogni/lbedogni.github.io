# Communication-Efficient Multi-Modal Edge Inference via Uncertainty-Aware Distributed Learning

**Source:** [arXiv:2601.14942](https://arxiv.org/abs/2601.14942)
**Date:** Jan 2026
**Field:** Multi-modal Edge Inference, Semantic Communication, Distributed Learning

## Summary
This paper proposes a unified three-stage framework to improve the efficiency and robustness of multi-modal edge inference (MMEI) over bandwidth-limited wireless links, focusing on semantic communication (transmitting meaning rather than bits).

## Key Contributions
1. **Local Self-Supervised Pre-training (Stage I):** Devices perform local learning to obtain shared and modality-specific encoders, eliminating the need for initial device-server exchange and reducing training communication rounds.
2. **Evidential Fusion (Stage II):** Uses evidential uncertainty to calibrate per-modality reliability and aggregate features distorted by noise or channel fading.
3. **Uncertainty-Guided Feedback (Stage III):** An adaptive retransmission policy that selectively requests additional features only for samples with high uncertainty, optimizing the communication-accuracy tradeoff.

## Analysis & Relevance
Extremely relevant to **Distributed Edge Inference** and **IoT**. It tackles the "communication bottleneck" of multi-modal data (RGB, Depth, etc.) by using semantic representations and uncertainty-aware logic. The focus on robustness to channel noise and modality degradation is critical for real-world edge deployments.

## Results
- Reaches target accuracy with **10x to 20x fewer training communication rounds** than baselines.
- Higher final accuracy and strong robustness even when one modality is severely degraded.
