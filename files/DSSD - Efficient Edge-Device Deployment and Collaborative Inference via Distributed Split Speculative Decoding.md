---
title: "DSSD: Efficient Edge-Device Deployment and Collaborative Inference via Distributed Split Speculative Decoding"
date: 2026-07-14
type: entity
source: "https://arxiv.org/abs/2507.12000"
tags: [LLM, Speculative Decoding, Split Computing, Edge Computing, Collaborative Inference]
---

# DSSD: Efficient Edge-Device Deployment and Collaborative Inference via Distributed Split Speculative Decoding

## Summary
DSSD addresses the communication bottlenecks associated with deploying Large Language Models (LLMs) across device-edge systems. It employs a collaborative architecture where a Small Language Model (SLM) on the device generates "draft" tokens (speculative decoding), which are then verified by an LLM at the edge. DSSD's key innovation is the "Split" verification phase: instead of the device sending full vocabulary distributions (heavy uplink), it optimizes the process so that the edge server's verification results are sent back as a single downlink transmission.

## Analysis
This paper is a direct application of **Split Computing** and **Collaborative Inference** to the current LLM wave. By partitioning the verification phase, DSSD effectively solves the "vocabulary distribution" communication overhead, which is a known pain point in distributed speculative decoding. This makes the deployment of high-quality LLMs on resource-constrained devices far more feasible by minimizing uplink traffic.

## Key Contributions
- Proposed a Distributed Split Speculative Decoding (DSSD) framework.
- Partitioned the verification phase of speculative decoding between device and edge.
- Significantly reduced communication latency and payload while maintaining the full inference quality of the target LLM.
- Provided open-source implementation: https://github.com/JasonNing96/DSSD-Efficient-Edge-Computing
