# Bayes-Split-Edge: Collaborative Inference Optimization

- **Topic:** Edge Computing, Distributed Edge Inference, Split Computing
- **Reference:** [Bayes-Split-Edge: Bayesian Optimization for Constrained Collaborative Inference in Wireless Edge Systems](https://arxiv.org/html/2510.23503v1)
- **Summary:**
  - Addresses collaborative inference (split computing) between resource-constrained edge devices (e.g., AR/VR headsets) and edge servers in wireless networks.
  - Formulates a utility optimization problem to maximize inference performance under strict energy and delay constraints.
  - Proposes *Bayes-Split-Edge*, a framework leveraging Bayesian Optimization (BO) to jointly optimize neural network split points and transmission power.
  - Features a novel hybrid acquisition function that balances inference utility, sample efficiency, and constraint violation penalties.
- **Results:**
  - Evaluated using VGG19 on ImageNet-Mini and Resnet101 on Tiny-ImageNet, with real-world wireless channel datasets.
  - Achieves up to 2.4x reduction in evaluation cost compared to standard BO and achieves near-linear convergence.
  - Outperforms common baselines (CMA-ES, DIRECT, PPO) and matches exhaustive search under tight constraints.
  - Requires a maximum of 20 function evaluations, making it highly sample-efficient for dynamic environments.
