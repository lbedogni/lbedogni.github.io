---
title: "Lightweight User-Personalization Method for Closed Split Computing (SALT)"
date: 2026-07-07
type: entity
source: "https://arxiv.org/abs/2603.14958"
tags: [Split Computing, Personalization, Edge AI, SALT]
---

# SALT: Split-Adaptive Lightweight Tuning

## Summary
SALT (Split-Adaptive Lightweight Tuning) is a framework for adapting "closed" Split Computing systems where the model architectures and parameters of the head and tail networks are inaccessible.

## Key Contributions
- **Client-Side Adapter**: Introduces a compact adapter that refines intermediate representations produced by a frozen head network.
- **No Overhead**: Enables adaptation without modifying the original networks or increasing communication costs.
- **Versatility**: Supports multiple objectives, including user personalization, communication robustness (handling packet loss), and privacy-aware inference.
- **Results**:
    - Improved personalized accuracy on CIFAR-10 from 88.1% to 93.8%.
    - Reduced training latency by >60%.
    - Maintains >90% accuracy even with 75% packet loss.

## Analysis
Extremely relevant for real-world deployments where proprietary models are used (closed systems). The ability to personalize and maintain robustness against network instability without retraining the core model is a significant practical advantage.
