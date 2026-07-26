# PrivyNAS: Privacy-Aware Neural Architecture Search for Split Computing in Edge–Cloud Systems

**Authors:** Mohanad Odema, Mohammad Abdullah Faruque
**URL:** https://ieeexplore.ieee.org/abstract/document/10239258

## Summary
PrivyNAS is a Neural Architecture Search (NAS) framework specifically designed for split computing in edge-cloud systems, where the primary goal is to protect user privacy. In traditional split computing, the transmission of intermediate feature maps from the edge device to the cloud can inadvertently leak sensitive information about the raw input data. PrivyNAS addresses this by treating privacy as a primary design objective. Using the **$\epsilon$-differential privacy (DP)** standard, the framework analyzes how different architectural parameters affect the "intrinsic privacy budget." It then automatically searches for an optimal DNN architecture that maximizes predictive accuracy while ensuring the transmitted data satisfies a strict privacy constraint.

## Analysis of Results
The researchers conducted an intensive empirical analysis of the relationship between DNN architecture and privacy. Their findings reveal that architectural choices—such as the depth of the "head" model and the specific layers chosen for the split—have a measurable impact on the amount of information that can be reconstructed from the intermediate features. By integrating this privacy metric into the NAS process, PrivyNAS is able to discover architectures that offer significantly stronger privacy guarantees than standard models, with only a marginal trade-off in accuracy.

## Key Takeaways
- Intermediate feature maps in split computing are not inherently private and can be exploited to reconstruct sensitive input data.
- **Differential Privacy (DP)** provides a rigorous mathematical foundation for quantifying and controlling the privacy leakage in distributed AI.
- Privacy-aware NAS allows for the automated discovery of "privacy-by-design" architectures, ensuring that the split point and model structure are optimized for both performance and data protection.

#toread #edge-computing #split-computing #iot
