---
title: "Communication-Efficient Collaborative LLM Inference over LEO Satellite Networks"
date: 2026-04-06
type: entity
source: "https://arxiv.org/abs/2604.04654"
tags: [LLM, LEO Satellites, Distributed Inference, Pipeline Parallelism]
---

# Communication-Efficient Collaborative LLM Inference over LEO Satellite Networks

## Summary
This paper proposes a collaborative inference scheme for deploying Large Language Models (LLMs) across a network of Low Earth Orbit (LEO) satellites. To overcome the memory limits of individual satellites, the LLM is split into sub-models distributed across the constellation. The system utilizes pipeline parallelism to overlap the computation of sub-models with the transmission of intermediate activations. It further employs an adaptive activation compression scheme and a modified A*-based search algorithm to minimize inference delay while satisfying accuracy and memory constraints.

## Analysis
This research effectively applies distributed edge inference principles to the challenging environment of satellite networks. The integration of pipeline parallelism and adaptive compression is crucial for mitigating the high latency and limited bandwidth inherent in inter-satellite links. Reducing delay by 42% and communication by 71% makes on-orbit LLM deployment significantly more viable for Earth observation and space-based AI.
