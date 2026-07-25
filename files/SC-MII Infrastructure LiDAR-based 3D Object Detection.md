---
title: "Infrastructure LiDAR-based 3D Object Detection on Edge Devices for Split Computing with Multiple Intermediate Outputs Integration"
date: 2026-01-12
type: entity
source: "https://arxiv.org/abs/2601.07119"
tags: [split-computing, lidar, 3d-object-detection, autonomous-driving, edge-computing]
---

# SC-MII: Infrastructure LiDAR-based 3D Object Detection

## Summary
The paper proposes **SC-MII**, a Split Computing architecture for 3D object detection using multiple infrastructure-mounted LiDARs. The system partitions a deep neural network such that edge devices (at the LiDAR sites) process local point clouds through initial layers, and then send multiple intermediate outputs to an edge server for final integration and inference.

## Key Results
- **Speed-up**: Achieved a **2.19x speed-up** in overall inference.
- **Edge Load**: Reduced edge device processing time by **71.6%**.
- **Accuracy**: Maintained performance with a negligible drop of at most **1.09%**.

## Analysis
By integrating multiple intermediate outputs, SC-MII reduces the "blind spot" problem of single LiDAR setups while keeping the heavy lifting on the server. The significant reduction in edge processing time makes this highly scalable for smart city infrastructure.
