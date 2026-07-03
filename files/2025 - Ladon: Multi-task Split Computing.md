# A Multi-task Supervised Compression Model for Split Computing (Ladon)

**Venue:** WACV 2025 / arXiv:2501.01420
**URL:** https://arxiv.org/abs/2501.01420

## Summary
The paper introduces "Ladon", the first supervised compression model specifically designed for multi-task split computing. Split computing involves partitioning a DNN between a resource-constrained device (sensor/mobile) and an edge server. Ladon focuses on learning compressed representations in the early layers to handle multiple tasks simultaneously without the usual degradation in accuracy or increase in latency.

## Key Contributions
- **Multi-task Support:** Extends split computing from single-task (e.g., just classification) to multi-task scenarios.
- **Supervised Compression:** Implements a compression model that reduces the data transmitted from device to server.
- **Efficiency:** Achieved significant reductions in end-to-end latency (up to 95.4%) and energy consumption (up to 88.2%) on mobile devices.

## Analysis & Relevance
Relevant to **Split Computing**. The ability to support multiple tasks using a single split point and compressed representation is a critical step toward versatile edge AI. The drastic reduction in energy and latency validates the approach for battery-powered IoT devices.
