# SCIoT: Design and Evaluation of a Split Computing Framework for the Internet of Things

- **Source:** IEEE / Semantic Scholar
- **URL:** https://ieeexplore.ieee.org/document/11366406
- **Field:** Split Computing / IoT / TinyML

## Summary
SCIoT is an intelligent framework for Split Computing in IoT that dynamically manages the partitioning of AI models between resource-constrained IoT devices and more powerful edge servers.

## Key Contributions
- **Adaptive Partitioning:** Automatically decides the split point based on current resource availability, network performance (fluctuations), and data sensitivity.
- **Heterogeneity Support:** Designed to work across a variety of heterogeneous IoT devices.
- **Efficiency:** Optimizes the trade-off between local compute (slow) and cloud offloading (bandwidth-heavy).

## Analysis
SCIoT is a foundational framework for Luca's IoT and Split Computing research. Its ability to account for *data sensitivity* is particularly important for edge computing, where privacy often dictates that certain layers must remain local.
