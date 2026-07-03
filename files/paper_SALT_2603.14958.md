# Paper: Lightweight User-Personalization Method for Closed Split Computing (arXiv:2603.14958)

## Summary
The paper introduces SALT (Split-Adaptive Lightweight Tuning), a framework for adapting split computing systems in "closed" environments where original model architectures and parameters are inaccessible. SALT utilizes a client-side adapter that refines intermediate representations produced by a frozen head network.

## Analysis
- **Key Contribution:** Enables effective model personalization and robustness (packet loss, noise) without requiring access to the full model, which is a significant practical hurdle in real-world deployments.
- **Results:** Experiments on ResNet-18 (CIFAR-10/100) showed personalization accuracy improvement (88.1% to 93.8%), 60% reduction in training latency, and maintained high accuracy under packet loss and noise injection.
- **Relevance:** Highly relevant to split computing/distributed inference in resource-constrained IoT settings.
