---
title: "Lightweight User-Personalization Method for Closed Split Computing"
date: 2026-03-16
type: entity
source: "https://arxiv.org/abs/2603.14958"
tags: [split_computing, personalization, edge_inference]
---

# Lightweight User-Personalization Method for Closed Split Computing

## Summary
This paper proposes **SALT (Split-Adaptive Lightweight Tuning)**, a framework designed for "closed" Split Computing systems where model architectures and parameters are inaccessible.

## Key Contributions
- **Client-Side Adapter**: Introduces a compact adapter that refines intermediate representations from a frozen head network.
- **No Model Modification**: Achieves adaptation without modifying the head or tail networks, avoiding increased communication overhead.
- **Versatile Objectives**: Supports user personalization, communication robustness, and privacy-aware inference.

## Analysis & Results
- **Performance**: Improved personalized accuracy from 88.1% to 93.8% on CIFAR-10.
- **Efficiency**: Reduced training latency by over 60% compared to conventional retraining/fine-tuning.
- **Robustness**: Maintains >90% accuracy under 75% packet loss and high accuracy under noise injection.
- **Verdict**: Highly practical for real-world deployments where model weights cannot be changed.
