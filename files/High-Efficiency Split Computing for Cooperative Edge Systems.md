---
title: "High-Efficiency Split Computing for Cooperative Edge Systems: A Novel Compressed Sensing Bottleneck"
date: 2025-04-15
type: entity
source: "https://arxiv.org/abs/2504.15295"
tags: [split-computing, compressed-sensing, edge-ai, bandwidth-efficiency]
---

# High-Efficiency Split Computing for Cooperative Edge Systems

## Summary
This paper proposes a novel split computing (SC) architecture designed to address the challenges of bandwidth constraints and the trade-off between accuracy and real-time performance in edge systems.

## Core Contribution: HECS-B
The authors introduce the **High-Efficiency Compressed Sensing Bottleneck (HECS-B)**. 
- **Mechanism**: It integrates a compressed sensing autoencoder into the shallow layers of a Deep Neural Network (DNN).
- **Method**: Uses knowledge distillation to create a bottleneck layer that efficiently compresses intermediate feature data.
- **Goal**: Preserve critical information for seamless reconstruction in the cloud while minimizing the data transmitted from the edge.

## Key Results
- **Bandwidth**: Reduces bandwidth utilization by **50%** compared to state-of-the-art methods.
- **Efficiency**: Achieves a **60% speed-up** in computational efficiency.
- **Accuracy**: Maintains high accuracy despite the significant compression.

## Relevance
Highly relevant to Luca's work on **Split Computing** and **Distributed Edge Inference**, specifically in optimizing the communication bottleneck between edge and cloud.
