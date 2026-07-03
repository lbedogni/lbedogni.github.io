# Edge Intelligence through in-sensor and near-sensor computing for the AI of Things
**Source:** Nature (2025)
**URL:** https://www.nature.com/articles/s44335-025-00040-6
**Tags:** #EdgeComputing #InSensorComputing #CIM #Neuromorphic #IoT

## Summary
This perspective explores the transition from centralized von Neumann architectures to decentralized sensor-edge computing to overcome energy, latency, and bandwidth bottlenecks.

### Key Concepts
- **In-Sensor Computing**: Integrates computation directly into sensor pixels.
    - Uses analog compute-in-memory (CIM) with non-volatile memories (memristors, FETs).
    - Enables massively parallel MAC operations in the analog domain.
    - Ideal for pre-processing and event-driven feature extraction.
- **Near-Sensor Computing**: Places dedicated computing units immediately adjacent to sensors.
    - Focuses on minimizing external memory access.
    - Relies on algorithm optimization: quantization, pruning, and sparse coding.
    - Integrates federated learning for privacy and reduced communication.

## Analysis
The paper highlights a fundamental shift toward neuromorphic hardware. For Luca's work on Distributed Edge Inference, this suggests that the "edge" is moving even further—from the edge server/gateway down to the physical sensor itself. The use of memristors and analog computing could drastically change the efficiency of split computing by allowing the first "split" to happen in the analog domain.
