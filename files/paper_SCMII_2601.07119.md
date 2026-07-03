# Paper: Infrastructure LiDAR-based 3D Object Detection on Edge Devices for Split Computing with Multiple Intermediate Outputs Integration (arXiv:2601.07119)

## Summary
The paper proposes SC-MII, a split computing framework for 3D object detection using LiDAR point cloud data. Edge devices perform initial processing of local point clouds and transmit intermediate features to an edge server for final inference.

## Analysis
- **Key Contribution:** Addresses the blind spot issue in single LiDAR setups and high computational demands by using infrastructure LiDARs and split computing to reduce latency and improve privacy.
- **Results:** Achieved a 2.19x speed-up and a 71.6% reduction in edge device processing time with minimal accuracy impact (1.09%).
- **Relevance:** Relevant to distributed edge inference and autonomous driving/smart city IoT scenarios.
