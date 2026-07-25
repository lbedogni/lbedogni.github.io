# GA-MO: Pareto-Optimal Split Computing for Deep Edge Intelligence

**Authors:** Hoang Trung Le, et al.
**URL:** https://doi.org/10.1142/S219688882650003X

## Summary
This paper proposes **GA-MO**, a genetic-algorithm-based multi-objective optimization framework for hybrid edge–cloud inference. The goal is to jointly optimize end-to-end latency and communication overhead, addressing a gap in existing Dynamic Split Computing (DSC) approaches that primarily focus on latency. GA-MO constructs Pareto fronts across diverse bandwidth conditions, allowing for the adaptive runtime selection of split configurations. It explores combinations of split points, quantization levels, compression ratios, and batch sizes.

## Analysis of Results
Extensive simulations using EfficientNet-B0 and VGG16 demonstrate that GA-MO consistently outperforms DSC and weighted-sum baselines:
- **Latency Reduction:** 55–60% improvement.
- **Bandwidth Savings:** 52–62% reduction in communication cost.
- **Performance:** Achieved a 100% win rate across all tested scenarios.

## Key Takeaways
- **Multi-Objective Focus:** Jointly minimizing latency and communication is more effective than optimizing them separately or through simple weighted sums.
- **Adaptive Selection:** Constructing Pareto fronts enables the system to pick the optimal operating point based on real-time bandwidth, making it highly scalable.
- **Comprehensive Exploration:** Including quantization and compression alongside split points provides a more granular and effective optimization space.

#toread #edge-computing #split-computing #iot #optimization
