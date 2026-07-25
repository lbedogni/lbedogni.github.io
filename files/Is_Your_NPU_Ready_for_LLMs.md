# Is Your NPU Ready for LLMs? Dissecting the Hidden Efficiency Bottlenecks in Mobile LLM Inference
**Date:** July 6, 2026
**Summary:** This research dissects the performance of NPUs (Neural Processing Units) compared to CPUs for mobile LLM inference. It identifies a "phase split" where NPUs are superior for compute-bound prefilling, but CPUs outperform them during memory-bound decoding.
**Analysis:** Very relevant for Luca's work on Edge Computing and Distributed Inference. Understanding the hardware-specific bottlenecks (NPU vs CPU) is crucial for optimizing split computing strategies, as the split point could be dynamically adjusted based on the current phase of inference (prefilling vs decoding).
**Search Link:** https://arxiv.org/search/?query=Is+Your+NPU+Ready+for+LLMs