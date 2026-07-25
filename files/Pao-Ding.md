---
title: "Pao-Ding: Accelerating Cross-Edge Video Analytics via Automated CNN Model Partitioning"
date: 2026-07-05
type: entity
source: "https://ieeexplore.ieee.org/document/11195759"
tags: [IoT, Edge Computing, Split Computing, Video Analytics, Distributed Inference]
---

# Pao-Ding

## Summary
Pao-Ding is a framework for **cross-edge video analytics**, where video data is processed collaboratively among multiple edge devices (rather than just one device and one server).

Key innovations include:
- **Automated Partitioning**: Uses **gradient information** to automatically parse the structure of CNN models.
- **Broad Support**: Supports partitioning for chain, simple Directed Acyclic Graph (DAG), and complex DAG models.
- **Efficiency**: Employs a **layer-pruning-based algorithm** to reduce computational overhead.

## Key Results
- Accelerates video analytics by optimizing the distribution of sub-models across a cluster of edge devices.
- Improves frame rates and accuracy for complex video tasks.

## Relevance to Luca
Directly impacts **Distributed Edge Inference** and **Split Computing**, specifically moving from the "Edge-Cloud" paradigm to a "Cross-Edge" (Edge-to-Edge) paradigm.
