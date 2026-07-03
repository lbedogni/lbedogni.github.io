# A Multi-task Supervised Compression Model for Split Computing

- **Venue**: WACV 2025 / arXiv:2501.01420
- **Date**: Jan 2025
- **Field**: Split Computing / Feature Compression

## Summary
This research proposes a supervised compression model for split computing that is capable of handling multiple tasks simultaneously. While traditional split computing models are typically optimized for a single task (e.g., just image classification), this model provides a generalized compression mechanism.

## Key Contributions
- **Multi-task Support**: Enables a single compression model to serve multiple downstream tasks such as classification and object detection.
- **Communication Efficiency**: Reduces the bandwidth required to transmit features from the edge device (sensor) to the edge server.

## Analysis
The shift from task-specific to multi-task compression is a major step toward practical split computing. In a real IoT deployment, an edge device often needs to perform various analyses on the same data stream. Avoiding the need for multiple compression models saves memory on the device and simplifies the pipeline.

#Tags: #SplitComputing #Compression #MultiTaskLearning #WACV2025 #EdgeAI
