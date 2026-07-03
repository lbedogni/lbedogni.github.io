# Enhancing Split Computing and Early Exit Applications through Predefined Sparsity

**Authors:** Luigi Capogrosso, et al.
**URL:** https://arxiv.org/abs/2407.11763

## Summary
This paper introduces a method to enhance Split Computing (SC) and Early Exit (EE) frameworks by incorporating **predefined sparsity**. Split Computing divides a DNN between an edge device and a remote server, while Early Exit allows the system to terminate processing at the edge if the result is sufficiently accurate, avoiding the trip to the server. By applying predefined sparsity to these paradigms, the authors reduce the computational, storage, and energy requirements during both the training and inference phases.

## Analysis of Results
The study demonstrates that the application of predefined sparsity leads to significant efficiency gains without compromising the model's performance. Specifically, the researchers observed reductions exceeding **4x in both storage and computational complexity**. These improvements were consistent across different hardware platforms, proving the generalizability of the approach.

## Key Takeaways
- Combining predefined sparsity with SC and EE creates a multi-layered optimization strategy for edge AI.
- Significant reductions in memory footprint and compute cycles can be achieved without losing accuracy.
- This approach makes it feasible to deploy more complex DNNs for real-time, real-world tasks on the most resource-constrained edge devices.

#toread #edge-computing #split-computing #iot
