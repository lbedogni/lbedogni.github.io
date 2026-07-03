# Clairvoyant: Predictive SJF Scheduling to Mitigate Head-of-Line Blocking in Serial LLM Backends
**Authors:** Aravind Sundaresan
**Link:** https://arxiv.org/abs/2606.07248
**Date:** 2026-06-08

## Summary
Clairvoyant is a sidecar proxy for serial LLM backends (like Ollama or llama.cpp) designed to mitigate Head-of-Line Blocking (HOLB). In memory-constrained edge deployments, continuous batching is often impossible. Clairvoyant uses a lightweight XGBoost classifier to predict response length from 19 lexical features, enabling Shortest Job First (SJF) scheduling. 
- **Performance:** Achieves 70-76% P50 latency reduction for short requests under high pressure.
- **Key Insight:** Curated instruction datasets are poor for length prediction; natural conversation logs are necessary.

## Analysis & Relevance
Directly relevant to **Distributed Edge Inference**. Deploying LLMs on the edge often involves severe memory constraints. Optimizing the request queue through length prediction is a practical way to improve Quality of Service (QoS) without needing the massive VRAM required for batching.
