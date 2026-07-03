---
title: "DSSD: Efficient Edge-Device Deployment and Collaborative Inference via Distributed Split Speculative Decoding"
date: 2026-06-24
type: entity
source: "https://arxiv.org/abs/2507.12000"
tags: [Split Computing, Speculative Decoding, LLM, Edge Computing, Distributed Inference]
---

# DSSD: Efficient Edge-Device Deployment and Collaborative Inference via Distributed Split Speculative Decoding

## Summary
DSSD proposes a novel architecture for the collaborative deployment of Large Language Models (LLMs) between devices and the edge. It optimizes Speculative Decoding (SD), where a Small Language Model (SLM) on the device drafts tokens and an LLM at the edge verifies them.

## Key Concepts
- **Distributed Split Speculative Decoding (DSSD)**: Partitions the verification phase of speculative decoding between the device and the edge.
- **Communication Optimization**: Replaces the heavy uplink transmission of multiple vocabulary distributions (from SLM to edge) with a single downlink transmission of a vocabulary distribution (from LLM to device), significantly reducing communication overhead.
- **Collaborative Inference**: Maintains the accuracy of the larger LLM while leveraging the speed of the local SLM.

## Analysis
This paper is highly relevant to **Split Computing** and **Distributed Edge Inference**. The "split" here isn't just about the model layers, but about splitting the *logic* of the verification process to minimize bandwidth usage. For LLM deployment at the edge, communication is often the primary bottleneck; DSSD's approach to shifting the data flow from uplink to downlink is a clever architectural optimization.

## Status
- [ ] Read full paper
- [ ] Check GitHub repository for implementation details
