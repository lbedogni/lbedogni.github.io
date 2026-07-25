# A Multi-task Supervised Compression Model for Split Computing (Ladon)

- **Source**: [arXiv:2501.01420](https://arxiv.org/abs/2501.01420) (Accepted at WACV 2025)
- **Tags**: #SplitComputing #EdgeAI #MultiTaskLearning #ModelCompression

## Summary
The paper introduces **Ladon**, the first multi-task-head supervised compression model specifically designed for split computing. Split computing partitions a DNN between a resource-constrained edge device (sensor/mobile) and a more powerful edge server. 

The authors identify that existing split computing methods, which typically focus on single tasks, suffer from accuracy degradation and increased latency when applied to multi-task scenarios. Ladon solves this by learning compressed representations in early layers that are shared across multiple tasks.

## Key Results
- **Performance**: Rivaled or outperformed strong lightweight baselines on ILSVRC 2012, COCO 2017, and PASCAL VOC 2012 datasets.
- **Latency**: Reduced end-to-end latency by up to **95.4%**.
- **Energy**: Reduced energy consumption on mobile devices by up to **88.2%**.

## Analysis for Luca
This is highly relevant to your work on **Split Computing**. The focus on multi-task capabilities is a significant step forward from single-task split-DNNs, enabling more versatile edge devices that can perform multiple inferences (e.g., classification + segmentation) with a single split-point and compressed transmission.
