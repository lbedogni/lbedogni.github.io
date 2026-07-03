# A Multi-task Supervised Compression Model for Split Computing (Ladon)

**Venue:** WACV 2025
**Tags:** #SplitComputing #MultiTaskLearning #ModelCompression #EdgeIntelligence

## Summary
The paper introduces **Ladon**, the first multi-task-head supervised compression model specifically for multi-task split computing. While previous split computing research focused on single tasks (e.g., just classification), Ladon uses a **unified image processing pipeline** to handle multiple tasks (ImageNet classification, COCO detection, PASCAL VOC segmentation) simultaneously.

## Key Analysis
- **Results:**
    - End-to-end latency reduction: up to **95.4%**.
    - Mobile device energy consumption reduction: up to **88.2%**.
    - Performance: Rivals or outperforms strong lightweight baseline models.
- **Innovation:** The use of a shared compressed representation for multiple downstream tasks significantly reduces the offloading data size and encoding cost on the local device.
- **Relevance to Luca:** Advanced application of Split Computing for multi-tasking, emphasizing extreme efficiency in latency and energy.
