# RISE: Relay Inference and Online Scheduling for Efficient Edge-Device Collaborative Diffusion Model Services
**Date:** 2026-06-15
**Source:** arXiv:2606.17378

## Summary
RISE introduces a training-free relay mechanism for deploying text-to-image diffusion models at the network edge. It splits the denoising process: a large, high-fidelity model on the edge server handles the initial steps (shaping the semantic structure), and then hands off the intermediate latent to a lightweight model on the user device for final detail refinement. To optimize this in real-time, it employs a contextual bandit scheduler that considers prompt complexity, user preferences, network quality, and node loads.

## Analysis
The core insight is that latent intensity remains stable during model handoff within the same model family, eliminating the need for costly retraining. This approach effectively bridges the gap between high-latency/high-fidelity and low-latency/low-fidelity models, making generative AI more practical for mobile devices.

## Key Results
- Achieved up to **2.1x speedup** in inference.
- Preserved full-model quality.
- Effective balance of quality and latency under mixed workloads.
