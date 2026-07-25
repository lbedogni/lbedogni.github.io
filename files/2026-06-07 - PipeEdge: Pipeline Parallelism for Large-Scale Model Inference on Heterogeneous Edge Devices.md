# PipeEdge: Pipeline Parallelism for Large-Scale Model Inference on Heterogeneous Edge Devices

**Authors:** Hu, Imes, et al.
**URL:** https://ieeexplore.ieee.org/document/9996638

## Summary
PipeEdge is a distributed inference framework designed to enable the deployment of large-scale AI models (such as Transformers) on clusters of memory-constrained edge devices. While traditional split computing often focuses on a single device-server pair, PipeEdge implements **pipeline parallelism**. It shards the model across multiple devices and processes different parts of the model in a pipelined fashion, allowing the system to handle larger models than could fit on any single device while simultaneously increasing throughput by processing multiple requests in parallel. The framework includes an automatic partition scheduler that maps model layers to devices based on their specific compute, memory, and network bandwidth capabilities.

## Analysis of Results
By employing pipeline parallelism, PipeEdge significantly increases the overall system throughput compared to sequential distributed execution. The authors demonstrate that their optimal partitioning strategy minimizes "pipeline bubbles" (idle time where a device waits for data from a previous stage), ensuring that heterogeneous hardware is utilized at maximum efficiency. The results show that PipeEdge can effectively run state-of-the-art large models on a cluster of low-power edge devices with minimal latency penalty.

## Key Takeaways
- Pipeline parallelism is an essential technique for scaling model inference beyond the memory limits of a single edge device.
- Considering hardware heterogeneity (compute/memory/network) during the partitioning phase is critical for avoiding bottlenecks in a distributed pipeline.
- The shift from simple split computing to pipelined distributed inference allows for a significant increase in the volume of requests a cluster of edge devices can handle per second.

#toread #edge-computing #split-computing #iot
