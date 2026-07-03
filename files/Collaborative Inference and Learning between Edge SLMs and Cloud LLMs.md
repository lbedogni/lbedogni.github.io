---
title: "Collaborative Inference and Learning between Edge SLMs and Cloud LLMs: A Survey of Algorithms, Execution, and Open Challenges"
date: 2025-07-22
type: entity
source: "https://arxiv.org/abs/2507.16731"
tags: [LLM, SLM, Edge Computing, Collaborative Inference, Survey]
---

# Collaborative Inference and Learning between Edge SLMs and Cloud LLMs

## Summary
This is a comprehensive survey exploring the collaborative paradigm between **Small Language Models (SLMs)** deployed on edge devices and **Large Language Models (LLMs)** hosted in the cloud. The paper provides a unified taxonomy of collaboration strategies across both inference (task assignment, division, and mixture-based collaboration) and training (distributed adaptation, pruning, and distillation).

## Analysis
As LLMs grow in size, the "cloud-only" or "edge-only" (via extreme compression) approaches are insufficient. This paper bridges the gap by analyzing how SLMs and LLMs can cooperate at both the task and token granularity. It's a crucial read for understanding the systemic architecture of edge-cloud intelligence, covering everything from speculative decoding to resource-aware offloading.

## Key Contributions
- A unified taxonomy for edge-cloud collaboration in LLM/SLM contexts.
- Categorization of inference strategies: task assignment, division, and mixture-based.
- Review of distributed adaptation techniques for training/fine-tuning.
- Summary of benchmarks and privacy-preserving methods for collaborative intelligence.
