---
title: "ET-SCS: Error-Tolerant Split Computing System for Internet of Things"
date: 2026-06-12
type: entity
source: "https://ieeexplore.ieee.org/abstract/document/11456673"
tags: [Split Computing, IoT, Robustness, Error Tolerance]
---

# ET-SCS: Error-Tolerant Split Computing System for Internet of Things

## Summary
ET-SCS proposes an **Error-Tolerant Split Computing System** specifically tailored for the constraints of IoT environments, where transmission errors in intermediate data can significantly degrade model performance.

### Key Mechanisms
- **Error-Aware Training**: The edge cloud trains the model by explicitly considering potential transmission errors that occur when intermediate tensors are sent from the IoT device to the server.
- **Dynamic Filtering**: The system introduces a dynamic filtering mechanism that automatically adjusts filter coefficients in real-time to improve robustness against noise and transmission faults.

## Analysis & Results
- **Robustness**: By incorporating error tolerance into the training phase and applying dynamic filtering during inference, ET-SCS maintains higher accuracy than traditional split computing schemes in unstable network conditions.
- **Efficiency**: It allows for the deployment of more complex models on low-power IoT devices by offloading the bulk of the computation while mitigating the risks associated with unreliable edge-to-cloud links.

## Relevance to Luca's Research
Strongly relevant to **Split Computing** and **IoT**. It addresses the practical reality of "dirty" data transmission in distributed systems, moving beyond the assumption of perfect communication channels in split-inference research.
