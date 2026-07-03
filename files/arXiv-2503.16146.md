# [2503.16146] Distributed Split Computing Using Diffusive Metrics for UAV Swarms

**Date:** Mar 2025 / Apr 2026
**Field:** Split Computing, UAV Swarms, Distributed Intelligence

## Summary
Presents a fully distributed approach to split computing for large-scale UAV swarms, removing the need for centralized orchestration.

**Key Innovations:**
- **Aggregated Gigaflops:** A new iterative, diffusive metric that captures local and neighborhood compute capacity without requiring global network knowledge.
- **Intelligent Forwarding:** Partial inferences are forwarded to underutilized nodes based on the diffusive metric.
- **Early-Exit Mechanism:** Adapts the inference pathway on-the-fly to handle workload surges or changing node conditions.

## Analysis
While applied to UAVs, the core contribution is the *diffusive metric* for task partitioning. This provides a scalable alternative to centralized orchestrators, which are often a single point of failure or a communication bottleneck in highly dynamic edge networks.

**Relevance to Luca:** High. Directly addresses Split Computing and Distributed Edge Inference in highly dynamic environments.
