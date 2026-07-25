---
title: "Infrastructure LiDAR-based 3D Object Detection on Edge Devices for Split Computing with Multiple Intermediate outputs Integration (SC-MII)"
date: 2026-07-07
type: entity
source: "https://arxiv.org/abs/2601.07119"
tags: [Split Computing, 3D Object Detection, LiDAR, Edge Computing]
---

# SC-MII

## Summary
SC-MII proposes a method for 3D object detection using multiple infrastructure LiDARs distributed across edge devices, utilizing Split Computing with Multiple Intermediate outputs Integration.

## Key Contributions
- **Multi-LiDAR Integration**: Addresses blind spots of single LiDAR setups by integrating data from multiple infrastructure-based sensors.
- **Split Architecture**: Edge devices process initial DNN layers and transmit multiple intermediate outputs to an edge server for final integration.
- **Efficiency**: 
    - 2.19x speed-up in inference.
    - 71.6% reduction in edge device processing time.
    - Minimal accuracy loss ($\le 1.09\%$).

## Analysis
Relevant for intelligent transport systems (ITS) and autonomous driving. It demonstrates how Split Computing can be used to combine spatial data from multiple sensors while keeping the heavy compute on the server, reducing the load on the physical infrastructure sensors.
