---
title: "DSSD: Efficient Edge-Device Deployment and Collaborative Inference via Distributed Split Speculative Decoding"
date: 2026-07-14
type: entity
source: "https://arxiv.org/abs/2507.12000"
tags: [Edge Computing, LLM, Speculative Decoding, Collaborative Inference, SLM]
---

# DSSD: Efficient Edge-Device Deployment and Collaborative Inference via Distributed Split Speculative Decoding

## Summary
DSSD proposes a novel architecture for deploying Large Language Models (LLMs) in a device-edge collaborative system. It optimizes **Speculative Decoding (SD)** to reduce the communication bottleneck associated with verifying draft tokens.

## Key Concepts
- **SLM-LLM Split**: A Small Language Model (SLM) on the device generates draft tokens, and a Large Language Model (LLM) at the edge verifies them.
- **Distributed Split Speculative Decoding (DSSD)**: Unlike standard DSD which transmits full vocabulary distributions uplink for verification, DSSD partitions the verification phase. It replaces multiple uplink distributions with a single downlink transmission from the LLM.

## Analysis
The primary contribution is the **reduction of communication overhead**. By splitting the verification process, DSSD avoids the linear dependency of the communication payload on the vocabulary size. This allows for high-quality LLM inference with significantly lower latency and power consumption on the mobile device, making "Edge LLMs" more viable.

## Reference
- Source: [[https://arxiv.org/abs/2507.12000]]
- Code: [GitHub](https://github.com/JasonNing96/DSSD-Efficient-Edge-Computing)
