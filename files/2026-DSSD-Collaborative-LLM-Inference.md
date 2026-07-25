# DSSD: Efficient Edge-Device Deployment and Collaborative Inference via Distributed Split Speculative Decoding

**Source**: [arXiv:2507.12000](https://arxiv.org/abs/2507.12000)
**Venue**: ICML 2025
**Key Fields**: Edge Computing, Collaborative Inference, LLMs, Speculative Decoding

## Summary
DSSD proposes a novel architecture for deploying Large Language Models (LLMs) in device-edge systems. It addresses the communication overhead of speculative decoding, where a Small Language Model (SLM) on the device suggests tokens and an LLM at the edge verifies them.

## Analysis
The primary innovation is the **Distributed Split Speculative Decoding**, which partitions the verification phase. Instead of the device sending multiple vocabulary distributions uplink (which is costly), DSSD optimizes the transmission to use a single downlink transmission, significantly reducing latency without sacrificing the accuracy of the LLM. This is a critical advancement for real-time LLM interactions on resource-constrained devices.

## Relevance to Luca's Research
Directly applies to **Distributed Edge Inference** and **Split Computing**, specifically extending these concepts to the domain of Generative AI and LLMs.
