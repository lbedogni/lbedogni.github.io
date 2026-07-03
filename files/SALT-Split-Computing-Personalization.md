# SALT: Lightweight User-Personalization Method for Closed Split Computing

- **Source**: [arXiv:2603.14958](https://arxiv.org/abs/2603.14958)
- **Category**: Split Computing, Edge AI Adaptation
- **Key Contribution**: Proposes SALT (Split-Adaptive Lightweight Tuning), an adaptation framework for closed Split Computing systems.
- **Mechanism**:
	- Uses a compact client-side adapter that refines intermediate representations produced by a frozen head network.
	- No modification to head or tail networks required.
- **Results**:
	- Improves personalized accuracy (e.g., 88.1% to 93.8% on CIFAR-10).
	- Reduces training latency by >60%.
	- Robust to high packet loss (75%) and noise injection.
- **Analysis**: A very practical approach to Split Computing where the server model is inaccessible. It bridges the gap between performance and the realities of unstable edge networks.
- **Status**: To Read / Analyze further
