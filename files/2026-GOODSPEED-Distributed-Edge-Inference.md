# GOODSPEED: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference

- **Venue:** IEEE INFOCOM 2026
- **URL:** https://arxiv.org/abs/2512.09963
- **Field:** Distributed Edge Inference / LLMs

## Summary
This paper proposes GOODSPEED, a framework designed to accelerate Large Language Model (LLM) inference in distributed edge environments using adaptive speculative decoding. It coordinates multiple heterogeneous "draft servers" (running small models) and a central "verification server" (running a large model).

## Key Contributions
- **Adaptive Speculative Decoding:** Uses draft models to predict tokens, which are then verified in parallel by the central server.
- **Fairness-Aware Scheduling:** Implements a gradient scheduling algorithm that maximizes a logarithmic utility function, ensuring proportional fairness in resource allocation across different draft servers.
- **Theoretical Guarantees:** Uses fluid sample path analysis to prove convergence to optimal goodput in steady-state and bounded error under dynamic workloads.

## Analysis
This is highly relevant to Luca's interest in Distributed Edge Inference. The shift towards deploying LLMs at the edge makes "speculative decoding" a critical optimization. The focus on *fairness* among heterogeneous servers is a practical addition for real-world distributed systems where nodes have varying capabilities.
