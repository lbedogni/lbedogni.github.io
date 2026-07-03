---
title: "SCIoT: Design and Evaluation of a Split Computing Framework for the Internet of Things"
date: 2026-06-12
type: entity
source: "https://ieeexplore.ieee.org/document/11366406"
tags: [Split Computing, IoT, TinyML, Adaptive Partitioning]
---

# SCIoT

## Summary
SCIoT is an intelligent framework for Split Computing in the IoT domain, aimed at optimizing the trade-off between local execution on resource-constrained devices and offloading to edge servers.

## Analysis
The framework focuses on **adaptive partitioning**. Instead of a static split point, SCIoT dynamically decides which parts of a machine learning model to run locally and which to offload. This decision is based on:
- **Resource Availability**: Current CPU/Memory of the device.
- **Network Performance**: Fluctuating bandwidth and latency.
- **Data Sensitivity**: Ensuring sensitive data is processed locally.

### Key Results
The system makes TinyML applications more efficient by reducing bandwidth waste (compared to full offloading) and reducing latency (compared to full local execution).

## Relevance to Luca's Field
This is a foundational approach to **Split Computing** and **IoT**, focusing on the practical deployment of AI on heterogeneous edge hardware.
