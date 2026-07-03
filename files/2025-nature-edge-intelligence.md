# Edge intelligence through in-sensor and near-sensor computing for the artificial intelligence of things

**Source:** Nature (2025)
**URL:** https://www.nature.com/articles/s44335-025-00040-6
**Tags:** #EdgeComputing #IoT #DistributedInference #AIoT #InSensorComputing

## Summary
This perspective provides a comprehensive overview of the shift from centralized computing architectures (von Neumann) to decentralized sensor-edge computing. It highlights the critical "data-transfer bottleneck" where the energy and latency costs of moving data from sensors to CPUs/GPUs (often in the cloud) become prohibitive.

### Key Technical Approaches:
- **In-Sensor Computing:** Integrates computational functionality (primarily analog) directly into the sensor pixels. Uses Compute-In-Memory (CIM) with non-volatile resistive memories (memristors, FETs) to perform parallel multiply-accumulate (MAC) operations at the source.
- **Near-Sensor Computing:** Employs dedicated computing units immediately adjacent to the sensor. Focuses on minimizing off-chip interfaces and utilizes aggressive optimization techniques like quantization, pruning, and sparse coding to fit models into constrained on-chip memory.
- **Algorithmic Shift:** Employs event-driven processing, spiking neural networks (SNNs), and federated learning to distribute training and inference across multiple sensor nodes.

## Analysis & Relevance
This paper is highly relevant to the research on **Distributed Edge Inference** and **Split Computing**. It argues that the most efficient "split" occurs at the very interface of sensing and processing. By moving the first layers of a neural network (feature extraction) into the sensor itself, the system can drastically reduce the amount of data that needs to be transmitted to the rest of the edge/cloud hierarchy.

**Key takeaway for Luca:** The integration of analog CIM at the sensor level represents the physical limit of "distributed inference," effectively turning the sensor into a primary compute node.
