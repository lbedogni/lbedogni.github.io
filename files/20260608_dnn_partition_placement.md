# Design Insights into Partition Placement and Routing for DNN Inference in Multi-Hop Edge Networks

**Date:** 2026-06-08
**Field:** Distributed Edge Inference, DNN Partitioning, Edge Networking

## Summary
This paper investigates the optimal placement of DNN partitions and the associated routing in multi-hop edge networks. It seeks to minimize end-to-end latency for intelligent services by strategically distributing model layers across multiple edge nodes.

## Analysis
This is a fundamental "Split Computing" problem: where to cut the model and where to place the pieces. The multi-hop aspect adds a layer of networking complexity (routing) that is often ignored in simple client-server split models. This is directly aligned with Luca's research in Distributed Edge Inference.

## Reference
arXiv (Submitted April 28, 2026)
