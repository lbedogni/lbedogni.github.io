# Distributed Split Computing Using Diffusive Metrics for UAV Swarms
**Source:** [arXiv:2503.16146](https://arxiv.org/abs/2503.16146)
**Date:** 2025 (revised 2026)
**Tags:** #SplitComputing #DistributedInference #UAVSwarms #EdgeComputing

## Summary
This paper proposes a fully distributed, diffusive metric-based approach for split computing in large-scale UAV swarms to overcome the limitations of centralized orchestration (communication bottlenecks, latency, and reliability).

### Key Contributions:
- **Aggregated Gigaflops**: A new iterative measure that captures a node's own computing capacity and that of its neighbors without requiring global network knowledge.
- **Intelligent Forwarding**: Partial inferences are forwarded to underutilized nodes to improve throughput and lower latency.
- **Early-Exit Mechanism**: An on-the-fly adaptation of the inference pathway to handle workload surges and changing node conditions.

## Analysis
The transition to a diffusive, decentralized metric for resource discovery is critical for highly dynamic topologies like drone swarms. By avoiding a central orchestrator, the system becomes more scalable and resilient to node failure or rapid movement. The combination of split computing with an early-exit strategy allows for a flexible trade-off between accuracy and latency, which is essential for real-time aerial intelligence.
