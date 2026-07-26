# DISNET: Distributed Micro-Split Deep Learning in Heterogeneous Dynamic IoT

**Authors:** Eric Samikwa, Antonio Di Maio, Torsten Braun
**URL:** https://ieeexplore.ieee.org/document/10243578

## Summary
DISNET proposes a distributed "micro-split" deep learning scheme tailored for heterogeneous and dynamic IoT environments. While traditional split computing focuses on a vertical split (dividing a model between an edge device and a server), DISNET introduces a hybrid approach. It combines **vertical partitioning** with **horizontal partitioning**, allowing the workload to be distributed and executed in parallel across multiple heterogeneous IoT devices. This enables a more flexible and granular distribution of the neural network's computational requirements, leveraging the collective resources of the IoT network.

## Analysis of Results
The framework achieves a significant reduction in overall inference latency and per-device energy consumption. By employing horizontal splitting, DISNET effectively mitigates the bottlenecks associated with single-device processing and the potential congestion of a single edge-to-cloud link. The parallel execution across multiple peer devices ensures that the system can maintain high throughput even in dynamic environments where device availability and resource capacities vary.

## Key Takeaways
- Hybrid partitioning (vertical + horizontal) is more effective for heterogeneous IoT environments than simple vertical splitting.
- Leveraging peer-to-peer collaboration among IoT devices (horizontal splitting) transforms a set of resource-constrained devices into a powerful distributed inference engine.
- DISNET provides a scalable architecture for low-latency, energy-efficient cooperative deep learning in the IoT.

#toread #edge-computing #split-computing #iot
