# Infrastructure LiDAR-based 3D Object Detection on Edge Devices for Split Computing with Multiple Intermediate Outputs Integration
- **URL:** https://arxiv.org/abs/2601.07119
- **Date:** 2026-01-12
- **Tags:** #SplitComputing #EdgeComputing #LiDAR #AutonomousDriving

## Summary
Proposes **SC-MII**, a framework for 3D object detection using infrastructure LiDAR. It utilizes Split Computing where edge devices process local point clouds and send *multiple* intermediate outputs to an edge server for integration and final inference.

## Results
- **Latency:** 2.19x speed-up in total inference.
- **Compute:** 71.6% reduction in edge device processing time.
- **Accuracy:** Negligible drop in accuracy (max 1.09%).

## Analysis
The "Multiple Intermediate outputs Integration" is the key innovation here, allowing for a more flexible distribution of compute and potentially better feature aggregation from multiple LiDAR sources, which is essential for eliminating blind spots in autonomous driving.
