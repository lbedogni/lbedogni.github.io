# Edge intelligence through in-sensor and near-sensor computing for the AIoT
**Source:** Nature (https://www.nature.com/articles/s44335-025-00040-6)
**Date Found:** 2026-07-01

## Summary
This paper discusses the transition from centralized computing architectures (CPU/GPU/Cloud) to decentralized "Edge Intelligence" specifically at the sensor level. It aims to overcome the von Neumann bottleneck—the energy and latency cost of moving data between memory and processors.

## Key Concepts
- **In-Sensor Computing:** Integrates computation directly into sensor pixels. Uses analog Compute-in-Memory (CIM) and multifunctional materials (memristors, FETs) to perform multiply-accumulate (MAC) operations in the analog domain.
- **Near-Sensor Computing:** Places dedicated processing units immediately adjacent to the sensor array to minimize data transfer distance.
- **Technologies:** Employs non-volatile resistive memory, 2D materials (MoS2, graphene), and neuromorphic designs (SNNs, reservoir computing).
- **Applications:** Biomedical monitoring, autonomous systems, and AI-driven IoT platforms.

## Analysis for Luca
Highly relevant to **Distributed Edge Inference** and **Split Computing**. The "in-sensor" approach is an extreme form of splitting where the first layer of a neural network is effectively the sensor itself.
