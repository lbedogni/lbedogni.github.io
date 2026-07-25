---
title: "GA-MO: Pareto-Optimal Split Computing for Deep Edge Intelligence"
date: 2026-07-09
type: entity
source: "https://www.academia.edu/165006258/GA_MO_Pareto_Optimal_Split_Computing_for_Deep_Edge_Intelligence"
tags: [Split Computing, Optimization, Genetic Algorithm, Edge Intelligence]
---

# GA-MO: Pareto-Optimal Split Computing for Deep Edge Intelligence

## Summary
GA-MO introduces a genetic-algorithm (GA) based optimization framework to determine the optimal split point in deep neural networks for edge-cloud collaborative inference. The goal is to achieve a Pareto-optimal balance between end-to-end inference latency and communication overhead, rather than optimizing for a single metric.

## Analysis
Existing Dynamic Split Computing (DSC) methods often over-simplify the optimization target (e.g., only minimizing latency). GA-MO recognizes that in resource-constrained edge environments, the trade-off between local computation and the cost of transmitting large intermediate tensors is non-linear and complex. Using a genetic algorithm allows the system to explore a wider range of split configurations and provide a set of optimal solutions (Pareto front) depending on the current network state.

## Key Takeaways
- **Optimization**: Joint optimization of latency and communication overhead.
- **Method**: Genetic Algorithm for finding Pareto-optimal split points.
- **Benefit**: Better adaptability to heterogeneous hardware and varying network bandwidth.
