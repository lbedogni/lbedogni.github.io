# When Does Delegation Beat Majority? A Delegation-Based Aggregator for Multi-Sample LLM Inference

**Date:** 2026-06-06
**Field:** Distributed Edge Inference, LLMs

## Abstract
The paper proposes a "Delegation-Based Aggregator" for multi-sample LLM inference, moving beyond simple majority voting. It introduces two levers: "WHEN" (determining the weight of a voter's own selection based on letter entropy) and "WHOM" (splitting the remaining weight across peers using embedding cosine similarity). The approach requires no gold labels or additional training.

## Analysis
As LLMs are increasingly deployed in distributed edge environments, the cost of generating multiple samples to improve reliability is high. This paper provides a more nuanced way to aggregate these samples, potentially improving accuracy without increasing the number of samples. This is directly applicable to "Distributed Edge Inference" where different nodes might generate different samples.

## Key Takeaways
- Delegation-based aggregation outperforms simple majority voting in LLM sampling.
- Letter entropy and embedding cosine similarity are effective signals for weighting "voters".
- Zero-shot nature (no training needed) makes it easy to deploy on edge nodes.
