# Ladon: A Multi-task Supervised Compression Model for Split Computing

**Venue:** WACV 2025
**Topic:** Split Computing / Multi-task Learning
**Date:** February 2025

## Summary
Ladon introduces the first multi-task-head supervised compression model specifically for split computing. Traditional split computing (splitting a model between a client and a server) often focuses on single tasks. Ladon allows a single compressed representation to be sent from the client to the server, which can then be used for multiple tasks (e.g., classification, detection, segmentation).

## Key Contributions
- **Multi-task Unified Pipeline:** Replaces task-specific pipelines with a unified processing pipeline, significantly reducing the local encoding cost and energy consumption.
- **Supervised Compression:** Learns highly efficient compressed representations in the early layers of the model.
- **Efficiency Gains:**
	- End-to-end latency reduced by up to **95.4%**.
	- Local device energy consumption reduced by up to **88.2%**.
- **Accuracy:** Maintains or exceeds the performance of strong lightweight baseline models on ILSVRC 2012, COCO 2017, and PASCAL VOC 2012.

## Analysis
Ladon solves a major bottleneck in split computing: the "redundancy" of sending multiple different compressed features if multiple tasks are required. By compressing into a single, versatile representation, it maximizes the utility of the limited communication bandwidth between the edge device and the server.

**Related to:** Split Computing, Resource-Constrained AI, Multi-task Learning.
