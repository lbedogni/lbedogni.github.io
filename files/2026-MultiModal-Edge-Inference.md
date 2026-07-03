# Communication-Efficient Multi-Modal Edge Inference via Uncertainty-Aware Distributed Learning

**arXiv:** 2601.14942
**Date:** Jan 2026
**Field:** Multi-Modal Edge Inference, Semantic Communication

## Summary
The paper proposes a three-stage framework to optimize the lifecycle of multi-modal edge inference (MMEI), reducing communication overhead during both training and inference while increasing robustness against noisy inputs and unstable wireless channels.

## Framework Stages
1. **Local Self-Supervised Pre-training:** Devices use a decoupled loss to learn shared and modality-specific encoders locally (zero communication).
2. **Distributed Fine-tuning & Evidential Fusion:** Centralized fusion at the server uses evidential uncertainty to calibrate the reliability of each modality.
3. **Uncertainty-Guided Feedback:** At inference, the server selectively requests additional features only for samples with high uncertainty, optimizing the communication-accuracy trade-off.

## Results
- **Efficiency:** Achieves target accuracy with 10x to 20x fewer training communication rounds compared to contrastive pre-training or training from scratch.
- **Robustness:** Maintains high performance even when one modality is severely degraded.

## Analysis & Relevance
Directly hits **IoT, Edge Computing, and Distributed Edge Inference**. The use of "semantic communication" (transmitting meaning rather than bits) is a key trend in 6G and edge intelligence. The a-priori local pre-training is a practical solution for bandwidth-constrained IoT environments.

#toread #edge-inference #multimodal #semantic-comm #iot