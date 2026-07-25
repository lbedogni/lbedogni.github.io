---
title: "Vision Token Manipulation Attacks on Cloud-Edge Inference of Large Vision-Language Models"
date: 2026-07-02
type: entity
source: "https://arxiv.org/abs/2607.02819"
tags: [LVLM, CloudEdge, Security, TokenManipulation]
---

# Vision Token Manipulation Attacks on Cloud-Edge Inference of Large Vision-Language Models

## Summary
This paper investigates the security vulnerabilities of split computing in Large Vision-Language Models (LVLMs) where computation is divided between an edge device and a cloud server.

## Key Findings
- **Attack Surface**: The transmission of intermediate vision tokens from edge to cloud creates a man-in-the-middle (MITM) attack surface.
- **VTM-Attack**: By manipulating only **10%** of the transmitted vision tokens, an adversary can reduce model accuracy by up to **88.31%**.
- **Vulnerability**: This reveals a critical lack of robustness in current cloud-edge LVLM inference pipelines.

## Analysis
This is a critical paper for anyone designing distributed inference systems. It demonstrates that simply splitting the model is not enough; the communication link must be secured, or the model must be robust to token-level perturbations.
