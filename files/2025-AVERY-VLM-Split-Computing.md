# AVERY: Intent-Driven Adaptive VLM Split Computing via Embodied Self-Awareness

**arXiv:** 2511.18151
**Date:** Nov 2025 / March 2026
**Field:** Split Computing, VLM, UAVs, Disaster Response

## Summary
AVERY is an adaptive split computing framework for deploying Vision-Language Models (VLMs) on resource-constrained UAVs. It treats "operator intent" as a system objective to dynamically adjust the compute/communication split.

## Key Innovations
- **Dual-Stream Split:**
    - **Context Stream:** High-frequency, low-resolution for real-time situational awareness.
    - **Insight Stream:** Low-frequency, high-fidelity for deep, queryable analysis.
- **Self-Aware Controller:** Monitors network conditions and intent to select the optimal compression model and split point at runtime.

## Results
- **Accuracy:** 11.2% higher accuracy than standard image compression.
- **Energy:** 93.98% lower energy consumption compared to full on-device execution.
- **Stability:** Stays within 0.75% of the high-accuracy baseline during dynamic network fluctuations.

## Analysis & Relevance
Combines **Split Computing** with state-of-the-art **VLMs** in a high-stakes IoT scenario (disaster response). The distinction between "Context" and "Insight" streams is a clever architectural choice that mirrors human cognitive processing and solves the latency-fidelity trade-off.

#toread #split-computing #vlm #uav #disaster-response