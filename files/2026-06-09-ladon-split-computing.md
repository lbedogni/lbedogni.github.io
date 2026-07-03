# A Multi-task Supervised Compression Model for Split Computing (Ladon)
**Source:** WACV 2025
**URL:** https://openaccess.thecvf.com/content/WACV2025/papers/Matsubara_A_Multi-Task_Supervised_Compression_Model_for_Split_Computing_WACV_2025_paper.pdf
**Tags:** #SplitComputing #CollaborativeInference #ModelCompression #MultiTaskLearning

## Summary
Introduces **Ladon**, the first end-to-end supervised compression model for multi-task split computing in computer vision.

### Key Contributions
- **Unified Preprocessing**: One pipeline for multiple tasks (Classification, Detection, Segmentation), eliminating redundant processing.
- **Shared Encoder**: A lightweight local encoder (ResNet/ResNeSt) that compresses input into a representation $\hat{z}$ for transmission.
- **Supervised Compression**: Learns a bottleneck representation that preserves only task-relevant information, significantly reducing bandwidth compared to standard codecs.

### Results
- **Efficiency**: Reduced end-to-end latency by up to 95.4% and energy consumption by 65-88% on NVIDIA Jetson devices.
- **Footprint**: Encoder size is extremely small (0.5-0.9 MB), making it ideal for highly constrained IoT devices.

## Analysis
Ladon solves the "multi-task overhead" problem in collaborative inference. Instead of running three different split models for three different tasks, it uses one shared compressed representation. This is a highly practical approach for real-world IoT deployments where a single camera might need to perform multiple functions simultaneously.
