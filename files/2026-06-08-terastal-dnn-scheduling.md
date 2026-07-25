# Terastal: Layer-Variant-based Scheduling for Real-Time Multi-DNN Workloads on Heterogeneous Accelerators
**Authors:** Sing-Yao Wu, Fengshuo Song, Eli Bozorgzadeh
**Link:** https://arxiv.org/abs/2606.06818
**Date:** 2026-06-08

## Summary
Terastal is a framework for designing and scheduling layer variants of DNNs on heterogeneous accelerators to reduce latency gaps. It combines offline heterogeneity-aware virtual budget assignment with online scheduling to optimize accelerator mapping and variant selection.
- **Results:** Reduces deadline miss rates by 30-40% compared to FCFS/EDF, with minimal accuracy loss (~2.24%).

## Analysis & Relevance
Extremely relevant to **Split Computing**. The concept of "layer variants" and mapping specific layers to preferred accelerators is essentially the core of split computing optimization. This provides a formal framework for managing how DNN workloads are distributed across heterogeneous edge hardware.
