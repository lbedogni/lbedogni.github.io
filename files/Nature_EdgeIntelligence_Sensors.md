# Edge intelligence through in-sensor and near-sensor computing for the AIoT

- **Source**: [Nature (s44335-025-00040-6)](https://www.nature.com/articles/s44335-025-00040-6)
- **Tags**: #IoT #EdgeIntelligence #InSensorComputing #Neuromorphic

## Summary
A perspective paper on the transition from centralized computing (CPU/GPU) to decentralized **in-sensor** and **near-sensor** computing to overcome the "von Neumann bottleneck" (data transfer overhead).

- **In-Sensor Computing**: Embeds computation directly into sensor pixels using analog methods (e.g., memristors, analog compute-in-memory). This allows raw sensor output to be processed without ADC conversion.
- **Near-Sensor Computing**: Places dedicated computing units (analog/digital) immediately adjacent to the sensor array to minimize physical off-chip data transfer.

The paper highlights the use of non-volatile memories (HfOx, MoS2, etc.) and neuromorphic architectures (SNNs) to emulate biological sensory processing, enabling real-time feature extraction at the source.

## Key Benefits
- Dramatic reduction in **power consumption**, **latency**, and **bandwidth**.
- Improved **data privacy** by processing data before it ever leaves the sensor.

## Analysis for Luca
While more focused on the hardware/materials side, this is foundational for **IoT** and **Edge Computing**. The move toward "in-sensor" intelligence is the extreme limit of edge computing and provides the hardware justification for the software partitioning seen in split computing.
