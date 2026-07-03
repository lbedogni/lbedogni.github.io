# Lightweight User-Personalization Method for Closed Split Computing (SALT)

**Status:** To Read
**Date Found:** 2026-06-27
**Source:** arXiv:2603.14958
**URL:** https://arxiv.org/abs/2603.14958

## Summary
Introduces **SALT (Split-Adaptive Lightweight Tuning)**, a lightweight adaptation framework for "closed" split computing systems (where the head and tail networks are frozen and inaccessible). It uses a compact client-side adapter to refine intermediate representations.

## Key Contributions
- **Closed-System Adaptation**: Allows tuning without modifying the original model architecture.
- **Versatility**: Supports user personalization, communication robustness (handling packet loss), and privacy-aware inference.
- **Efficiency**: Significantly reduces training latency (over 60% reduction) while improving accuracy (e.g., 88.1% to 93.8% on CIFAR-10).
- **Robustness**: Maintains >90% accuracy under 75% packet loss.

## Relevance to Luca's Research
Highly relevant to **Split Computing** and **IoT**, specifically addressing the practical challenges of deployment in real-world, unreliable, and private environments.
