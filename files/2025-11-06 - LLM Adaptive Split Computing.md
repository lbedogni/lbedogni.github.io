# Memory- and Latency-Constrained Inference of Large Language Models via Adaptive Split Computing
- **URL:** https://arxiv.org/abs/2511.04002
- **Date:** 2025-11-06
- **Tags:** #LLM #SplitComputing #EdgeComputing #IoT #Quantization

## Summary
Proposes the first **autoregressive-aware split computing framework** for LLMs on IoT devices. It addresses the unique challenges of token generation and KV cache expansion using:
- **OPSC (One-Point Split Compression):** A mixed-precision quantization scheme to prevent OOM.
- **Two-stage Compression:** Combines Threshold Splitting (TS) and Token-wise Adaptive Bit Quantization (TAB-Q).

## Results
- **Speed:** 1.49x inference speedup.
- **Overhead:** Significant reduction in communication costs.
- **Quality:** Maintains or improves accuracy compared to SOTA quantization (SmoothQuant, OmniQuant).

## Analysis
LLM inference on the edge is notoriously difficult due to the memory footprint. This paper's focus on the *autoregressive* nature of the task (specifically the KV cache) makes it a significant contribution to distributed inference for generative AI.
