---
title: "RISE: Relay Inference and Online Scheduling for Efficient Edge-Device Collaborative Diffusion Model Services"
date: 2026-06-15
type: entity
source: "https://arxiv.org/abs/2606.17378"
tags: [Edge Computing, Diffusion Models, Collaborative Inference, Scheduling]
---

# RISE: Relay Inference and Online Scheduling for Efficient Edge-Device Collaborative Diffusion Model Services

## Summary
RISE is a training-free relay mechanism designed for text-to-image diffusion models deployed in edge-device environments. It addresses the tension between high-fidelity (large models) and low-latency (small models) by splitting the denoising process. The large model on the edge server handles the initial semantic structuring, and the intermediate latent is then passed to a smaller model on the user device for final detail refinement. A contextual bandit scheduler is used to dynamically select the optimal relay configuration based on prompt complexity, network conditions, and node loads.

## Analysis
This work is particularly interesting for its observation that latent intensity remains stable during model handoff within the same model family. By avoiding expensive training for split-model compatibility, RISE offers a practical path to high-quality, real-time generative AI at the edge. The 2.1x speedup while maintaining quality indicates a strong efficiency gain for heterogeneous edge deployments.
