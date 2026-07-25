---
title: "Efficient Edge-Device LLM Deployment and Collaborative Inference via Distributed Split Speculative Decoding"
date: 2025-07-16
type: entity
source: "https://arxiv.org/abs/2507.12000"
tags: [LLM, SLM, Split Computing, Speculative Decoding, Edge Computing]
---

# Efficient Edge-Device LLM Deployment and Collaborative Inference via Distributed Split Speculative Decoding

## Summary
The paper introduces **Distributed Split Speculative Decoding (DSSD)**, a novel architecture for collaborative LLM inference. It improves upon standard speculative decoding (where an SLM proposes tokens and an LLM verifies them) by partitioning the verification phase itself between the device and the edge. This eliminates the need to transmit multiple vocabulary distributions uplink, replacing them with a single downlink transmission.

## Analysis
DSSD specifically targets the communication bottleneck in split computing. In traditional speculative decoding, the uplink cost of sending multiple candidate distributions can be prohibitive. By splitting the verification process, DSSD significantly reduces communication latency without sacrificing the accuracy of the LLM's verification. This makes it highly practical for real-world edge-device deployments.

## Key Contributions
- Proposal of the DSSD architecture that partitions the verification phase.
- Significant reduction in uplink transmission costs compared to existing collaborative frameworks.
- Maintenance of high inference quality while reducing latency.
- Open-source implementation available on GitHub.
