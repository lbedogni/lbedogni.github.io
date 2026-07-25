# Ladon: A Multi-task Supervised Compression Model for Split Computing

- **Venue:** WACV 2025
- **URL:** https://arxiv.org/abs/2501.01420
- **Field:** Split Computing / Edge AI

## Summary
The paper introduces Ladon, the first multi-task-head supervised compression model specifically for split computing. While traditional split computing focuses on single tasks, Ladon enables efficient multi-tasking (classification, detection, segmentation) by using a unified image processing pipeline.

## Key Contributions
- **Unified Pipeline:** Reduces the encoding cost and energy on the local (weak) device by transferring a single compressed representation for multiple tasks.
- **Supervised Compression:** Learns compressed representations at early layers to minimize communication overhead.
- **Performance:** Dramatically reduces end-to-end latency (up to 95.4%) and mobile device energy consumption (up to 88.2%) compared to traditional multi-task pipelines.

## Analysis
Ladon addresses a major bottleneck in Split Computing: the inefficiency of running separate pipelines for different tasks. By unifying the "split" point and the compression, it maximizes the utility of the edge-cloud collaboration.
