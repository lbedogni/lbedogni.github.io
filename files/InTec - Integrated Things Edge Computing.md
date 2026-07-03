---
title: "InTec: integrated things-edge computing: a framework for distributing machine learning pipelines in edge AI systems"
date: 2026-07-02
type: entity
source: "https://arxiv.org/abs/2502.11644"
tags: [Edge Computing, IoT, Distributed Inference, Architecture]
---

# InTec: integrated things-edge computing

## Summary
InTec introduces a three-tier architecture (Things, Edge, Cloud) designed to distribute ML pipelines strategically across all three layers to mitigate the latency and bandwidth constraints of traditional cloud-based ML. 

Unlike two-tier models, InTec processes data at the point of generation (Things layer) and distributes remaining tasks between the Edge and Cloud. Validation using the MHEALTH dataset for human motion detection showed:
- **81.56% reduction in response time**
- **10.92% decrease in network traffic**
- **~22-26% reduction in energy consumption** at both edge and cloud layers.

## Analysis
The transition from a 2-tier (Edge-Cloud) to a 3-tier (Thing-Edge-Cloud) model is a significant architectural shift. By treating the "Thing" (the sensor/device itself) as a first-class compute layer, InTec maximizes the benefit of "Distributed Edge Inference." The dramatic reduction in response time makes this framework very promising for real-time healthcare or industrial monitoring.
