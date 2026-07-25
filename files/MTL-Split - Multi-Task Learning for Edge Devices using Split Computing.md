---
title: "MTL-Split: Multi-Task Learning for Edge Devices using Split Computing"
date: 2026-07-11
type: source
source: "https://dl.acm.org/doi/abs/10.1145/3649329.3655686"
tags: [split-computing, multi-task-learning, edge-devices, dnn]
---

# MTL-Split: Multi-Task Learning for Edge Devices using Split Computing

## Summary
MTL-Split addresses the challenge of running multiple inference tasks on resource-constrained edge devices. It uses split computing to share the early layers of a multi-task network across the edge-cloud boundary, reducing redundant computations.

## Analysis
Multi-tasking is a common requirement for IoT (e.g., a camera doing both object detection and activity recognition). Sharing the "backbone" of the network through split computing is an efficient way to scale these capabilities.
