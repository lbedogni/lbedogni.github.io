---
title: "Smart Split: Leveraging TinyML and Split Computing for Efficient Edge AI"
date: 2024
type: entity
source: "https://ieeexplore.ieee.org/document/10818181"
tags: [TinyML, split-computing, IoT, ESP32, Edge-AI]
---

# Smart Split: Leveraging TinyML and Split Computing for Efficient Edge AI

## Summary
This paper explores the integration of Tiny Machine Learning (TinyML) with split computing to implement AI on extremely resource-constrained IoT devices.

## Core Contribution
- **Implementation**: Demonstrates a split computing pipeline using an **ESP32 microcontroller** (edge) connected to a **Raspberry Pi** (edge server).
- **Focus**: Specifically looks at classification tasks where the first few layers of the model run on the ESP32 and the remainder on the Raspberry Pi.
- **Integration**: Combines the extreme resource efficiency of TinyML with the collaborative power of Split Computing.

## Key Results
- Demonstrates the feasibility of running a split-model on low-power microcontrollers.
- Provides experimental data on the latency and accuracy trade-offs when shifting the split point in a TinyML context.

## Relevance
Directly applicable to **IoT** and **Edge Computing** research, especially for deployment on microcontrollers (MCU-level edge inference).
