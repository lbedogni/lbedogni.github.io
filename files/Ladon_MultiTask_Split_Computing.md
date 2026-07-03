# A Multi-task Supervised Compression Model for Split Computing

- **Authors**: Yoshitomo Matsubara et al.
- **Venue**: WACV 2025
- **URL**: https://arxiv.org/abs/2501.01420
- **Tags**: #SplitComputing #EdgeComputing #MultiTaskLearning #MobileDevices

## Summary
This paper introduces **Ladon**, the first multi-task-head supervised compression model specifically designed for multi-task split computing. Split computing offloads parts of deep learning models from resource-constrained edge devices (like mobile sensors) to stronger edge servers. While existing methods handle single tasks well, multi-task applications typically suffer from degraded accuracy or increased latency.

## Key Analysis & Results
- **Innovation**: Employs a supervised compression model at early layers to learn compressed representations, reducing the data transmitted over the wireless channel.
- **Performance**:
    - Outperformed or rivaled lightweight baselines on ILSVRC 2012, COCO 2017, and PASCAL VOC 2012.
    - **Latency Reduction**: Up to **95.4%** reduction in end-to-end latency.
    - **Energy Efficiency**: Up to **88.2%** reduction in energy consumption on mobile devices.
- **Significance**: Demonstrates that multi-task split computing can be made highly efficient without sacrificing significant predictive performance, making it viable for real-time mobile AI applications.
