# Speculation at a Distance: Where Edge-Cloud Speculative Decoding Actually Pays Off

**Authors:** Yuan Lyu, Bharath Irukulapati, Jaya Prakash Champati
**Date:** Submitted 23 June, 2026
**Source:** arXiv

## Summary
Speculative decoding (SD) uses a small "draft" model to predict tokens and a large "target" model to verify them, significantly speeding up LLM inference. Traditionally, these are co-located. This paper investigates "speculation at a distance," where the draft model runs at the edge and the target model runs in the cloud. The authors analyze the network latency overhead and identify the specific conditions (model sizes, network speeds, and prompt types) where this distributed approach still provides a net gain in tokens-per-second.

## Analysis
Relevant to **Edge Computing** and **Distributed Inference** of LLMs. As LLMs move toward the edge, the balance between local drafting and cloud verification is a key architectural decision. This paper provides the empirical bounds for when this split is beneficial, which is useful for designing resource-efficient inference systems for edge-cloud hybrids.

**Key Takeaways for Luca:**
- Empirical analysis of network latency vs. speculative gain.
- Design patterns for distributed LLM inference.
- Optimal partitioning of draft/target models across edge-cloud boundaries.
