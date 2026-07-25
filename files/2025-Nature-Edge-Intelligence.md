# Edge intelligence through in-sensor and near-sensor computing for the artificial intelligence of things
**Source:** Nature (2025)
**URL:** https://www.nature.com/articles/s44335-025-00040-6

## Summary
This perspective paper explores the transition from centralized computing (CPU/GPU/Cloud) to decentralized "sensor-edge" computing to overcome the von Neumann bottleneck (data transfer overhead between sensor, memory, and compute).

### Key Concepts
- **In-Sensor Computing**: Processing occurs *inside* the sensor pixel.
    - Uses analog Compute-In-Memory (CIM) with memristors, FETs.
    - Enables massively parallel MAC operations, event-driven processing, and low-power feature extraction.
- **Near-Sensor Computing**: Processing occurs in dedicated units *immediately adjacent* to the sensor.
    - Employs sparse coding, quantization, and pruning to fit complex models in limited memory.
    - Leverages federated learning to maintain privacy and reduce communication overhead.

## Analysis
This represents the "extreme edge" of distributed inference. Instead of splitting a model between an edge device and a server, the "split" happens between the sensing element and the local processing unit. This is critical for ultra-low power IoT devices where the energy cost of moving data from the sensor to a separate processor is the primary bottleneck.

**Relevance to Luca's Field:**
- **IoT**: Direct implementation of AI in sensors.
- **Distributed Edge Inference**: Pushes the inference boundary to the physical transducer level.
- **Split Computing**: A physical manifestation of splitting the compute pipeline at the hardware level.
