---
title: "SALT: Split-Adaptive Lightweight Tuning for Closed Split Computing Personalization"
date: 2025-03-16
type: paper
source: "https://arxiv.org/abs/2603.14958"
arxiv: "2603.14958"
tags: [Split Computing, Personalization, Edge AI, Model Adaptation, Closed Systems]
---

# SALT: Split-Adaptive Lightweight Tuning for Closed Split Computing Personalization

## Key Info
- **arXiv:** [2603.14958](https://arxiv.org/abs/2603.14958)
- **Date:** March 2026
- **Source:** arXiv

## Summary
This paper introduces **SALT (Split-Adaptive Lightweight Tuning)**, a framework designed for **"closed" Split Computing** systems where the model architectures and parameters of the head (edge) and tail (cloud) networks are inaccessible. To solve the problem of performance degradation due to user-specific data shifts and unreliable networks, SALT adds a compact client-side adapter that refines the intermediate representations produced by the frozen head network, enabling adaptation without modifying the main networks or increasing communication overhead.

## Key Results
- **Personalization:** On CIFAR-10, personalized accuracy improved from **88.1% to 93.8%**
- **Efficiency:** Reduced training latency by over **60%** compared to conventional fine-tuning
- **Robustness:** Maintained >90% accuracy even with **75% packet loss**
- **Privacy:** High accuracy (approx 88%) maintained under noise injection ($\sigma = 1.0$)

## Analysis
Personalization in split computing is a subtle challenge: how do you personalize a model when the weights are split between two entities? This paper explores local adaptations at the edge (client-side) while keeping the heavy lifting on the server, which is a key architectural decision in split inference.

## Relevance to Research
Directly applicable to **Split Computing** research, specifically focusing on:
- The "closed" system constraint
- Lightweight adaptation for edge devices
- Privacy-preserving personalization in distributed inference scenarios

#toread #split-computing #personalization #edge-ai