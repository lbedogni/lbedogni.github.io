# DSSD: Efficient Edge-Device LLM Deployment and Collaborative Inference via Distributed Split Speculative Decoding
**Date:** 2025-07-16
**Source:** arXiv (Jiahong Ning et al.)

## Summary
DSSD introduces a framework for collaborative LLM inference that combines Small Language Models (SLMs) on devices with larger LLMs at the edge. It employs "Distributed Split Speculative Decoding," where the SLM generates draft tokens and the edge LLM verifies them in a split-computing fashion, significantly reducing the number of expensive edge-side iterations.

## Analysis
Speculative decoding is a powerful way to speed up LLM inference. By distributing the "drafting" (SLM) and "verification" (LLM) across the device-edge boundary, DSSD minimizes communication while maximizing the throughput of the larger model.

## Key Results
- Efficient deployment of LLMs on resource-constrained devices.
- Significant reduction in end-to-end inference latency compared to standard collaborative inference.
