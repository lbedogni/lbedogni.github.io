# Fast collaborative inference via distributed speculative decoding

**Source**: ScienceDirect ([Link](https://www.sciencedirect.com/science/article/pii/S2949715925000782))
**Date**: 2025/2026

## Summary
This research proposes Distributed Split Speculative Decoding (DSSD) to accelerate collaborative inference. Speculative decoding usually involves a small "draft" model and a larger "verification" model. DSSD partitions the verification phase between the edge device and the server.

## Key Contributions
- **DSSD Architecture**: Partitions the verification phase to optimize the communication flow.
- **Communication Optimization**: Sends a single vocabulary distribution in the downlink rather than multiple distributions in the uplink, significantly reducing uplink overhead.
- **Latency Reduction**: Improves the speed of collaborative LLM-style inference on the edge.

## Analysis & Relevance
Very relevant to **Distributed Edge Inference** and **Collaborative Computing**. Applying speculative decoding to the split computing paradigm is a cutting-edge approach to reducing the latency of Large Language Models (LLMs) at the edge.
