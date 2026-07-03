# [2601.14942] Communication-Efficient Multi-Modal Edge Inference via Uncertainty-Aware Distributed Learning

**Date:** Jan 2026
**Field:** Multi-modal Edge Inference, Semantic Communication, Distributed Learning

## Summary
Proposes a three-stage framework to improve the efficiency and robustness of multi-modal edge inference (MMEI) over wireless links.

**The Three-Stage Process:**
1. **Local Self-Supervised Pre-training:** Devices perform local learning to obtain shared/modality-specific encoders, eliminating device-server exchange during this phase.
2. **Distributed Fine-tuning with Evidential Fusion:** Calibrates per-modality uncertainty and aggregates features robustly, handling noise and channel fading.
3. **Uncertainty-Guided Feedback:** A mechanism that selectively requests additional features for uncertain samples to optimize the communication-accuracy tradeoff.

## Analysis
This work is significant for its "lifecycle-wide" approach, optimizing both the training and inference phases. The integration of evidential uncertainty to drive adaptive communication is a sophisticated way to handle the volatility of wireless edge environments.

**Relevance to Luca:** High. Covers IoT, Edge Computing, and Distributed Inference.
