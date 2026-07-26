# Federated learning and TinyML on IoT edge devices: Challenges, advances, and future directions
**Source:** ScienceDirect (https://www.sciencedirect.com/science/article/pii/S2405959525000839)
**Date Found:** 2026-07-01

## Summary
This research examines the synergy between Federated Learning (FL) and TinyML for resource-constrained IoT devices. It focuses on the challenges of implementing AI on the extreme edge where memory, power, and communication bandwidth are severely limited.

## Key Concepts
- **TinyML + FL:** Using FL to train models across distributed IoT devices without sharing raw data, while utilizing TinyML techniques (quantization, pruning) to fit models on microcontrollers.
- **Challenges:** Communication overhead, privacy leakage, and accuracy drops due to device heterogeneity.
- **Proposed Framework:** A novel FL-IoT framework that uses Over-the-Air (OTA) model updates and LoRa-based distributed communication to enable scalable edge learning.

## Analysis for Luca
Directly applies to **IoT** and **Distributed Edge Inference**. The use of LoRa for distributed model updates is a practical approach to the communication bottlenecks often found in split computing scenarios.
