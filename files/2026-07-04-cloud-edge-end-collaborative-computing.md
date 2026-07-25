# Research on cloud-edge-end distributed collaborative computing based on deep reinforcement learning

**Source:** Nature (s41598-025-32813-1)
**URL:** https://www.nature.com/articles/s41598-025-32813-1
**Fields:** Distributed Edge Inference, IoT, Resource Management, DRL

## Summary
This paper addresses the challenges of high-frequency, large-scale data acquisition in power distribution networks. The core problem is the inefficiency of cloud-only processing due to latency and instability, and the limited resources at the edge/terminal levels.

The authors propose **IDCEE** (Improved Deep Q-Network based Cloud–Edge–End Collaborative Processing Algorithm).

### Key Technical Contributions:
- **Lyapunov Optimization:** Uses virtual queues to transform the problem into an online optimization that ensures both latency and throughput.
- **Conflict Resolution:** A greedy strategy-based Q-value sorting mechanism to handle resource competition between multiple terminals for wireless channels and edge servers.
- **Convergence Improvement:** A dual replay experience pool to maintain sample diversity and improve the stability of the DRL agent.
- **Architecture:** A three-layer hierarchy (Terminal $\to$ Edge $\to$ Cloud) where tasks are dynamically offloaded based on current system state.

## Analysis
This work is highly relevant to **Distributed Edge Inference**. It treats the edge-cloud continuum as a collaborative system and uses DRL to solve the task offloading problem in a stochastic environment. The use of Lyapunov optimization to bridge short-term decisions with long-term stability is a strong architectural choice for real-time IoT systems.
