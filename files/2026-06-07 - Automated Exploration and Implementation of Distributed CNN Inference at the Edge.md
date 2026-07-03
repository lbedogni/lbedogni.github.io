# Automated Exploration and Implementation of Distributed CNN Inference at the Edge

**Authors:** Xiaotian Guo, Andy D. Pimentel, Todor Stefanov
**URL:** https://ieeexplore.ieee.org/document/10018439

## Summary
This paper presents a framework to enable the deployment of large, resource-intensive Convolutional Neural Networks (CNNs) on IoT edge devices through "horizontal" distributed inference. Instead of relying on cloud offloading or lossy model compression, the framework partitions a single CNN across a cluster of multiple, potentially heterogeneous, edge devices.

The framework's core is **AutoDiCE**, a tool that automates the splitting of pre-trained models (in ONNX format) and generates optimized C++ code for execution using a hybrid MPI (for inter-device communication) and OpenMP (for intra-device parallelism) approach. To navigate the vast search space of possible layer-to-device mappings, the authors developed a **Multi-stage Hierarchical Design Space Exploration (DSE)** method utilizing a Genetic Algorithm and a specialized **Split Point Encoding (SPE)** to find Pareto-optimal configurations for latency and energy.

## Analysis of Results
The system was evaluated using DenseNet-121, ResNet-101, and VGG-19 on a cluster of NVIDIA Jetson Xavier NX boards.
- **Resource Efficiency:** For ResNet-101, distributing the model across eight devices reduced the maximum per-device energy consumption by approximately **40%** and memory usage by **80%** compared to single-device execution.
- **Throughput:** Pipeline parallelism led to throughput increases of up to **38%** (DenseNet-121) and **18%** (ResNet-101/VGG-19) when scaling to four devices.
- **The Scaling Limit:** An important finding was the existence of a communication bottleneck; scaling from four to eight devices actually *decreased* throughput, as the inter-device communication overhead began to outweigh the gains from parallel computation.
- **DSE Performance:** The Split Point Encoding (SPE) was significantly faster and more effective at finding high-quality solutions than traditional naive encoding methods.

## Key Takeaways
- Distributed edge computing allows for the execution of high-accuracy, full-scale models on low-power hardware by sharing the workload.
- Automation (via AutoDiCE) is critical for making distributed inference accessible to developers who are not experts in parallel programming.
- The "Communication vs. Computation" trade-off defines the optimal number of devices; simply adding more nodes does not linearly increase performance.
- The framework extends the operational life of battery-powered devices by lowering the thermal and power load per unit.

#toread #edge-computing #split-computing #iot
