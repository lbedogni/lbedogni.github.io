# AC$^2$P$^2$SL: Adaptive Communication-Computation Pipeline Parallel Split Learning over Edge Networks

**Authors:** Chenyu Liu, Zhaoyang Zhang, Zirui Chen, Zhaohui Yang, Chunhui Feng, Tony Q. S. Quek
**Date:** Submitted 30 June, 2026
**Source:** arXiv

## Summary
The paper introduces AC$^2$P$^2$SL, a framework for Adaptive Communication-Computation Pipeline Parallel Split Learning. Split learning divides a neural network into two parts: one executed on the edge device and the other on a server. This paper focuses on optimizing the "pipeline" aspect—overlapping the communication of activations/gradients with the computation of subsequent layers—to minimize the idle time of both the device and the server in wireless edge networks.

## Analysis
This is a direct hit for **Split Computing** and **Distributed Edge Inference**. The focus on "Adaptive" pipeline parallelism suggests the system can adjust to varying network conditions (latency, jitter), which is critical for real-world IoT deployments. The use of pipeline parallelism to hide communication latency is a standard but essential optimization for split computing.

**Key Takeaways for Luca:**
- Advanced pipeline parallelism for split learning.
- Adaptation mechanisms for wireless network fluctuations.
- Reducing the communication bottleneck in split-model architectures.
