# Furcifer: Adaptive Split Computing for Real-Time Object Detection
**Source:** [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S1574119225000173)
**Date:** 2025
**Tags:** #SplitComputing #AdaptiveInference #ObjectDetection #EdgeComputing

## Summary
The paper introduces "Furcifer," a middleware designed for dynamic and seamless adjustments of adaptive split computing decisions across the cloud-edge continuum. It specifically targets real-time object detection in pervasive and mobile execution environments.

### Key Contributions:
- **Dynamic Splitting**: The middleware allows the system to adjust the split point of the neural network based on real-time network and compute conditions.
- **Cloud-Edge Continuum**: Optimizes the distribution of workload between mobile devices, edge nodes, and the cloud.

## Analysis
Furcifer addresses the "static" nature of many split computing implementations. In real-world mobile scenarios, network quality fluctuates; a fixed split point can lead to either bottlenecking at the device or excessive latency. The adaptive nature of this middleware makes split computing viable for high-bandwidth tasks like object detection in unpredictable environments.
