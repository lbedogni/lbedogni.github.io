# LO-SC: Local-Only Split Computing for Accurate Deep Learning on Edge Devices

**Authors:** Luigi Capogrosso, Enrico Fraccaroli, Marco Cristani, Franco Fummi, Samarjit Chakraborty
**URL:** https://ieeexplore.ieee.org/abstract/document/10900702

## Summary
LO-SC is a framework that enables the execution of large Deep Neural Networks (DNNs) on resource-constrained edge devices without relying on cloud servers or sacrificing accuracy. Unlike traditional Split Computing, which offloads parts of the model to a server, LO-SC splits the model into multiple segments that are processed sequentially **entirely on the edge device**. It employs a Mixed-Integer Linear Problem (MILP) optimization (treating layers as items in a constrained knapsack) to determine the optimal partitioning of the model to fit within the device's available RAM.

## Analysis of Results
The framework was tested on NVIDIA Jetson Nano (4GB) and Xavier NX (8GB) using VGG16 and MobileNetV1.
- **Accuracy:** Maintained **100% of the original model's accuracy**, significantly outperforming pruning and quantization (e.g., VGG16 accuracy remained at 85.55% compared to 77.23% for compressed versions).
- **Memory:** Successfully ran models that exceeded physical RAM by partitioning them into 2 to 4 segments.
- **Performance:** Local segment switching was found to be faster than transmitting feature maps over a gigabit network. For 1920px inputs, local switching took **~15.73 seconds**, while network transfer took **~44 seconds**.

## Key Takeaways
- Memory capacity, rather than compute power, is often the primary bottleneck for edge AI deployment.
- LO-SC removes the need for cloud connectivity, making it ideal for secure and isolated Operational Technology (OT) environments.
- The MILP approach allows for dynamic partitioning based on input resolution, ensuring that the largest possible segments fit into memory.

#toread #edge-computing #split-computing #iot
