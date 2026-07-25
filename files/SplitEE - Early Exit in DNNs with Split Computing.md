---
title: "SplitEE: Early Exit in Deep Neural Networks with Split Computing"
date: 2026-07-11
type: source
source: "https://dl.acm.org/doi/10.1145/3639856.3639873"
tags: [split-computing, early-exit, dnn, resource-constrained]
---

# SplitEE: Early Exit in Deep Neural Networks with Split Computing

## Summary
SplitEE combines two paradigms: split computing (offloading) and early exits (terminating inference early if a high-confidence result is reached). This allows the system to avoid offloading altogether for "easy" samples, saving both energy and bandwidth.

## Analysis
Integrating early exits with split computing creates a hierarchical decision process: 1) Can I solve it locally and quickly? 2) If not, where is the best place to split it for the cloud? This significantly optimizes resource usage.
