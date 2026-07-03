# Smart Split: Leveraging TinyML and Split Computing for Efficient Edge AI

- **Venue**: 9th Annual IEEE/ACM Symposium on Edge Computing (SEC) 2024
- **Date**: Dec 2024
- **Field**: TinyML / Split Computing / IoT

## Summary
The paper explores the integration of Tiny Machine Learning (TinyML) with split computing to implement efficient ML on extremely resource-constrained devices. The authors demonstrate a classification pipeline using an ESP32 microcontroller (edge device) and a Raspberry Pi (edge server).

## Key Contributions
- **Hardware Validation**: Proven implementation on ESP32 and Raspberry Pi.
- **Latency Focus**: Unlike many papers focusing only on accuracy, this work emphasizes the total time for image capture and classification.
- **Synergy**: Shows how TinyML can be used for the initial layers of a split model to reduce the data sent over the network.

## Analysis
This is a highly practical contribution (and involves Luca Bedogni). It bridges the gap between the "extreme edge" (microcontrollers) and the "near edge" (SBCs), providing a blueprint for deploying AI on hardware that is too small for even the smallest standard neural networks.

#Tags: #TinyML #SplitComputing #IoT #ESP32 #SEC2024 #LucaBedogni
