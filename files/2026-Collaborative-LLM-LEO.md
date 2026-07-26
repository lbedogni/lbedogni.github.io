# Communication-Efficient Collaborative LLM Inference over LEO Satellite Networks
**Date:** 2026-04-06
**Source:** arXiv:2604.04654

## Summary
This paper proposes a collaborative inference scheme for Large Language Models (LLMs) deployed across Low Earth Orbit (LEO) satellite networks. The LLM is partitioned into sub-models distributed across multiple satellites. It utilizes pipeline parallelism to overlap inference with the transmission of intermediate activations. To manage communication costs, it uses an adaptive activation compression scheme. The optimal splitting and compression ratios are determined via a modified A* search algorithm over a directed acyclic graph.

## Analysis
Dealing with the extreme constraints of satellite hardware (memory) and the dynamics of LEO networks (latency) requires a highly optimized partitioning strategy. The joint optimization of splitting and compression is a critical contribution for enabling "Space-Edge" AI.

## Key Results
- Reduced inference delay by up to **42%**.
- Reduced communication overhead by up to **71%**.
- Maintained accuracy loss of **less than 1%**.
