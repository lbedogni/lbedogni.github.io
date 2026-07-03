# A Multi-Task Supervised Compression Model for Split Computing (WACV 2025)

**Source:** [GitHub/WACV 2025](https://github.com/yoshitomo-matsubara/ladon-multi-task-sc2)

## Summary
This paper introduces **Ladon**, the first multi-task-head supervised compression model for split computing. It addresses the problem where applying existing single-task split computing methods to multi-task scenarios (e.g., combining classification, detection, and segmentation) leads to degraded accuracy or increased latency.

## Key Contributions
- **Unified Pipeline:** Instead of task-specific pipelines, Ladon uses a unified image processing pipeline that learns a shared compressed representation.
- **Efficiency:** Reduces encoding costs and data offloading size by transferring only one compressed representation from the local device to the edge/cloud server.
- **Performance:** 
    - Latency reduced by up to **95.4%**.
    - Energy consumption on mobile devices reduced by up to **88.2%**.
    - Predictive performance rivals or outperforms strong lightweight baselines on ILSVRC 2012, COCO 2017, and PASCAL VOC 2012.

## Analysis & Relevance
Highly relevant to **Split Computing** and **Edge Inference**. The shift from single-task to multi-task split computing is a critical step for real-world edge applications where a single sensor might need to perform multiple AI tasks simultaneously. The massive reduction in latency and energy makes this a strong candidate for resource-constrained IoT deployment.
