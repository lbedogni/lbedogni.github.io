---
title: "Empowering Edge Intelligence: A Comprehensive Survey on On-Device AI Models"
date: 2025-03-06
type: entity
source: "https://arxiv.org/html/2503.06027v1"
tags: [EdgeAI, OnDeviceAI, Survey, IoT]
---

# Empowering Edge Intelligence: A Comprehensive Survey on On-Device AI Models

## Summary
This survey explores the current state and future trends of AI models designed specifically for deployment on edge and terminal devices. It emphasizes the need for local data processing to achieve real-time performance, reduce bandwidth usage, and enhance data privacy.

### Key Technical Focus
- **Characteristics**: Local inference, resource constraints (compute, storage, energy), and low latency.
- **Optimization Strategies**: 
  - Data preprocessing.
  - Model compression (to fit hardware limits).
  - Hardware acceleration (e.g., NVIDIA Jetson, Google Coral).
- **Application Scenarios**: Smartphones, smart homes, autonomous vehicles, and medical devices.

## Analysis
For research in **Distributed Edge Inference** and **Split Computing**, this paper provides the necessary context on the "endpoint" constraints. It highlights the trade-off between accuracy and scalability in constrained environments, which is the primary driver for splitting models between the edge and the cloud (or other edge nodes). The discussion on foundation models (Gemma, Llama) being adapted for the edge shows that the trend is moving toward bringing LLM-like capabilities to the edge, which will likely necessitate more sophisticated split-computing architectures.
