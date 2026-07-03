# Delay-Adaptive Speculation Control for Low-Latency Edge-Cloud LLM Inference
## Summary
Addresses the challenge of low-latency LLM inference in distributed edge-cloud systems. Uses speculative decoding where a draft model proposes tokens and a target model verifies them. The paper introduces a delay-adaptive control mechanism to optimize draft lengths, improving latency performance compared to static methods.
## Analysis
This is highly relevant to Luca's work in distributed inference. The key contribution is adapting speculation parameters to dynamic edge-cloud network conditions. It addresses the overhead of distributed token verification, which is a core bottleneck in split computing/distributed LLMs.
