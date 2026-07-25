---
title: "ET-SCS: Error-Tolerant Split Computing System for Internet of Things"
date: 2026-07-09
type: entity
source: "https://ieeexplore.ieee.org/abstract/document/11456673"
tags: [Split Computing, IoT, Robustness, Error Tolerance]
---

# ET-SCS: Error-Tolerant Split Computing System for Internet of Things

## Summary
ET-SCS proposes an error-tolerant split computing framework specifically designed for IoT environments. Unlike traditional split computing that assumes reliable transmission of intermediate tensors, ET-SCS incorporates transmission errors directly into the training process at the edge cloud. To ensure robustness during inference, it employs a dynamic filtering mechanism that automatically adjusts filter coefficients based on the channel conditions.

## Analysis
The primary contribution of ET-SCS is its focus on the reliability of the communication link between the edge device and the server. In real-world IoT deployments, packet loss and noise in intermediate data can significantly degrade model performance. By making the model "error-aware" during training and adding a dynamic filter, ET-SCS provides a more resilient solution for unstable network environments.

## Key Takeaways
- **Training**: Model training considers expected transmission errors.
- **Inference**: Dynamic filtering adjusts to communication noise.
- **Application**: High-reliability requirements in IoT.
