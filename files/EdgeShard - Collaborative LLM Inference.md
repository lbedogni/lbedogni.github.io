# EdgeShard: Efficient LLM Inference via Collaborative Edge Computing

**Source:** [arXiv:2405.14371](https://arxiv.org/abs/2405.14371) | IEEE
**Date:** May 2024
**Keywords:** #LLM #CollaborativeComputing #EdgeInference #SplitComputing #DistributedSystems

## Summary
EdgeShard is a general LLM inference framework designed to support efficient collaborative execution across distributed edge devices and cloud servers. 
- **Core Problem:** LLMs are too large for single edge devices; cloud-only deployment causes latency and privacy issues.
- **Solution:** Partitions the LLM into "shards" and deploys them across a network of heterogeneous devices.
- **Optimization:** The partitioning process considers device computing power, memory capacity, and available bandwidth to optimize total inference latency.

## Analysis
This is a practical application of **Split Computing** and **Distributed Edge Inference**. By treating the LLM as a set of shards that can be distributed, EdgeShard demonstrates how to handle the heterogeneity of the edge. This is directly relevant to research on splitting computation between an IoT device and a nearby edge gateway or a distant cloud.

## Action Items
- [ ] Analyze the partitioning algorithm used by EdgeShard to see if it can be generalized to non-LLM models.
- [ ] Compare this "sharding" approach with other split-computing methods (e.g., early-exit or layer-wise splitting).
