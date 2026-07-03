# SCIoT: Design and Evaluation of a Split Computing Framework for IoT
**Source:** Semantic Scholar / UniMore
**URL:** https://www.semanticscholar.org/paper/SCIoT%3A-Design-and-Evaluation-of-a-Split-Computing-Lamazzi-Wang/e584899947f18c282d10a1b7bce3530c45946a3f
**Tags:** #SplitComputing #IoT #AdaptivePartitioning #CollaborativeInference

## Summary
SCIoT is a systems-level framework for Split Computing that focuses on the dynamic and heterogeneous nature of IoT environments.

### Key Features
- **Adaptive Partitioning**: Dynamically decides where to split the model based on:
    - **Resource Availability**: Available CPU/RAM on the device.
    - **Network Performance**: Current latency and bandwidth.
    - **Data Sensitivity**: Privacy requirements of the data.
- **Heterogeneity**: Designed to work across a variety of different device types in an IoT ecosystem.

## Analysis
While Ladon focuses on *how* to compress the data, SCIoT focuses on *where* to make the cut. This framework approach is essential for "Distributed Edge Inference" because it treats the split point as a variable rather than a constant, allowing the system to degrade gracefully or optimize performance based on the environment.
