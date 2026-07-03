---
title: "Optimizing Split Learning Latency in TinyML-Based IoT Systems"
date: 2026-07-02
type: entity
source: "https://arxiv.org/abs/2507.16594"
tags: [Split Computing, TinyML, IoT, Latency Optimization]
---

# Optimizing Split Learning Latency in TinyML-Based IoT Systems

## Summary
This paper investigates the inference latency of Split Learning (SL) on resource-constrained IoT hardware (ESP32-S3) using various wireless protocols. The authors benchmark UDP, TCP, ESP-NOW, and BLE, finding that **ESP-NOW** provides the best Round Trip Time (RTT) of 3.6s. 

To further reduce end-to-end latency, the paper analyzes the trade-off between communication and computation overhead by varying the split point in models like MobileNet-V2 and ResNet50. They propose a **Beam Search-based algorithm** for split point optimization that achieves near-optimal latency with minimal processing overhead (0.1s for 5 devices).

## Analysis
This is highly relevant for implementing split computing on very low-power devices. The discovery that ESP-NOW outperforms standard TCP/UDP/BLE is a practical takeaway for hardware selection and protocol implementation in TinyML systems. The Beam Search approach provides a scalable way to optimize the split point dynamically or statically.
