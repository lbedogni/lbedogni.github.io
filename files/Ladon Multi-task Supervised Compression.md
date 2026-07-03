---
title: "Ladon: A Multi-task Supervised Compression Model for Split Computing"
date: 2025-01-01
type: paper
source: "https://openaccess.thecvf.com/content/WACV2025/papers/Matsubara_A_Multi-Task_Supervised_Compression_Model_for_Split_Computing_WACV_2025_paper.pdf"
arxiv: "2501.01420"
tags: [Split Computing, Supervised Compression, Multi-task Learning, Edge Intelligence, Model Partitioning]
---

# Ladon: A Multi-task Supervised Compression Model for Split Computing

## Authors
Yoshitomo Matsubara, et al.

## Source
- WACV 2025
- arXiv: [2501.01420](https://arxiv.org/abs/2501.01420)

## Summary
Ladon is the first end-to-end multi-task supervised compression model designed for Split Computing (SC), allowing a single lightweight encoder on a mobile device to support multiple downstream tasks on an edge server simultaneously. It addresses the communication bottleneck in split computing where intermediate feature maps sent from device to edge server can be larger than the original input.

## Key Technical Contributions
- **Unified Encoder**: A single shared encoder (0.543 – 0.935 MB) extracts a compressed representation $\hat{z}$ used for Image Classification, Object Detection, and Semantic Segmentation simultaneously
- **Unified Preprocessing**: Eliminates the need for task-specific cropping/resizing on the device
- **Supervised Compression**: Replaces early layers of ResNet-50/ResNeSt-269e with encoder-decoder structures trained for task-agnostic feature extraction
- **Multi-task Heads**: Learns compressed representations in early layers used by multiple task-specific heads on the edge server

## Analysis & Results
- **End-to-End Latency**: Reduced by up to **95.4%** compared to lightweight baselines in multi-task scenarios
- **Energy Consumption**: Reduced by **65.0% to 88.2%** on NVIDIA Jetson devices
- **Efficiency**: Proves that supervised compression is more efficient than simply using "mobile" models (like MobileNet) when a powerful server is available for the backend
- **Footprint**: Encoder size is extremely small (0.5-0.9 MB), making it ideal for highly constrained IoT devices

## Key Takeaways
- Multi-task split computing is challenging because single-task compression doesn't generalize well
- Supervised compression of early layers is key to reducing communication overhead and device-side energy
- Ladon provides a scalable way to deploy multiple AI tasks on extremely resource-constrained sensors (e.g., drones, IoT nodes)
- The unified preprocessing and shared encoder approach is highly practical for real-world IoT deployments where a single camera might need to perform multiple functions

## Relevance to Research
Directly aligns with **Distributed Edge Inference** and **Split Computing**. The use of multi-task supervised compression to address communication overhead in collaborative inference is a sophisticated approach for resource-constrained IoT environments.

#toread #edge-computing #split-computing #iot #multi-task-learning