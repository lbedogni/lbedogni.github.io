---
title: "Efficient Edge-Device LLM Deployment and Collaborative Inference via Distributed Split Speculative Decoding"
date: 2026-07-02
type: entity
source: "https://arxiv.org/abs/2507.12000"
tags: [Edge Computing, LLM, Distributed Inference, Speculative Decoding]
---

# Distributed Split Speculative Decoding (DSSD)

## Summary
This paper addresses the challenges of deploying Large Language Models (LLMs) in device-edge systems. It proposes **Distributed Split Speculative Decoding (DSSD)**, which combines a Small Language Model (SLM) on the device with a larger LLM at the edge.

To reduce the communication overhead associated with the verification phase of speculative decoding, DSSD partitions the verification between the device and edge. Specifically, it replaces the uplink transmission of multiple vocabulary distributions with a single downlink transmission, significantly reducing communication latency while maintaining the accuracy of the original LLM.

## Analysis
This is a cutting-edge application of "Split Computing" applied to LLMs. Speculative decoding is a known technique to speed up LLM inference, but the "Split" aspect of DSSD solves the critical bottleneck of uplink bandwidth in edge scenarios. This is extremely relevant for any "AI-on-Edge" project involving generative AI.
