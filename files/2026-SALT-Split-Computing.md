# SALT: Lightweight User-Personalization Method for Closed Split Computing

**arXiv:** 2603.14958
**Date:** March 2026
**Field:** Split Computing, Model Adaptation

## Summary
SALT (Split-Adaptive Lightweight Tuning) is a framework for adapting "closed" split computing systems—where the internal parameters of the edge "head" and cloud "tail" networks are inaccessible. It introduces a compact client-side adapter to refine intermediate representations.

## Key Features
- **Closed-System Compatibility:** Does not require modifying the frozen head or tail networks.
- **Lightweight Tuning:** Only the small adapter is trained, significantly reducing training cost and latency.
- **Versatility:** Supports user personalization, communication robustness, and privacy-aware inference.

## Results
- **Accuracy:** Improved personalized accuracy from 88.1% to 93.8% on CIFAR-10.
- **Efficiency:** Reduced training latency by over 60%.
- **Robustness:** Maintains >90% accuracy under 75% packet loss.

## Analysis & Relevance
Perfect for **Split Computing**. The "closed system" constraint makes this highly applicable to real-world proprietary APIs or locked-down hardware. The focus on "user-personalization" at the edge is a crucial step for deploying generic models in diverse IoT environments.

#toread #split-computing #model-adaptation #personalization