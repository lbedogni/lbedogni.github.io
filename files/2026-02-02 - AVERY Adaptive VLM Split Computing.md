# Adaptive VLM Split Computing through Embodied Self-Awareness for Efficient Disaster Response Systems
- **URL:** https://arxiv.org/abs/2511.18151v2
- **Date:** 2026-02-02 (revised)
- **Tags:** #VLM #SplitComputing #EdgeComputing #UAV #DisasterResponse

## Summary
Introduces **AVERY**, a framework for deploying Vision-Language Models (VLMs) on UAVs. It moves beyond simple depth-wise partitioning to a **functional dual-stream split**:
1. **Context Stream:** High-frequency, low-resolution for real-time awareness.
2. **Insight Stream:** Low-frequency, high-fidelity for deep semantic analysis.

## Results
- **Accuracy:** 11.2% higher than raw image compression.
- **Energy:** 93.98% lower energy consumption compared to full-edge execution.
- **Performance:** Outperforms static configurations under fluctuating network conditions.

## Analysis
This represents a shift from *structural* splitting (where to cut the network) to *functional* splitting (what information to send and when). The "self-aware" controller that manages these streams based on network and intent is highly relevant for distributed edge inference.
