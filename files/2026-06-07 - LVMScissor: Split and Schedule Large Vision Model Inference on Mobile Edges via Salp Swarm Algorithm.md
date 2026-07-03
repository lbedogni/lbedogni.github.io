# LVMScissor: Split and Schedule Large Vision Model Inference on Mobile Edges via Salp Swarm Algorithm

**Authors:** Yanting Liu, Rui Lu, Dan Wang
**URL:** https://ieeexplore.ieee.org/document/10923690

## Summary
LVMScissor is an acceleration framework for deploying Large Vision Models (LVMs), specifically those based on Vision Transformers (ViT), on mobile edge devices. The core challenge addressed is the efficient partitioning and scheduling of these massive models. The authors model the parallelized ViT split problem as a Multi-task three-processor scheduling (MTS) problem and propose **LVM-MSSA**, a scheduling algorithm based on the Multi-objective Salp Swarm Algorithm (MSSA). LVM-MSSA optimizes both the model parallelism and the split strategy to achieve a better balance between computation and communication overhead.

## Analysis of Results
Evaluation results indicate that LVMScissor is faster than existing state-of-the-art inference acceleration approaches. By leveraging the Salp Swarm meta-heuristic, the framework can find near-optimal split points and scheduling orders that minimize end-to-end latency on mobile edge hardware, effectively overcoming the memory and compute bottlenecks of large transformer-based vision models.

## Key Takeaways
- Deploying Large Vision Models (LVMs) on the edge requires more than simple partitioning; it requires sophisticated scheduling of model parallelism.
- Meta-heuristic algorithms (like MSSA) are powerful tools for solving the NP-hard problem of optimal model splitting and scheduling across heterogeneous processors.
- LVMScissor enables the use of high-accuracy ViTs on mobile edges by reducing the latency associated with split inference.

#toread #edge-computing #split-computing #iot
