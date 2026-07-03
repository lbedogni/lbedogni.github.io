# Enhancing the Reliability of Split Computing Deep Neural Networks

**Authors:** Giuseppe Esposito, Juan-David Guerrero-Balaguera, Josie E. Rodriguez Condia, Marco Levorato, Matteo Sonza Reorda
**URL:** https://ieeexplore.ieee.org/document/10616071

## Summary
This research focuses on the reliability of Split Computing (SC) in safety-critical IoT applications, such as autonomous drones and biomedical devices. In an SC architecture, a "Head" model runs on a mobile device and a "Tail" model runs on a server. Hardware faults on the mobile device can introduce corrupted values into the feature maps, which then propagate and "explode" during the Tail's execution, leading to catastrophic failures. The authors propose two software-based hardening techniques:
1. **Adaptive Clipper:** Replaces ReLU with a bounded **HardTanH** activation function, with thresholds refined during a secondary training phase to limit the impact of faulty values.
2. **Saturation Quantizer:** A per-channel quantization strategy that clips feature map outliers (outside the 5th and 95th percentiles) before transmission.

## Analysis of Results
The techniques were evaluated using MobileNet V3 (classification) and SSD 300 (object detection).
- **Fault Reduction:** In image classification, the Adaptive Clipper reduced Critical Silent Data Corruptions (SDCs) from **17.73% to 14.31%**. For object detection, reliability improved by **5.73%** on average compared to other hardening methods.
- **Fault Masking:** The approach significantly increased the number of "masked" faults—errors that occur but do not change the final output.
- **Efficiency:** The computational overhead was extremely low, with the Saturation Quantizer adding only **0.018%** and the Adaptive Clipper adding **0.160%** to the processing time, both of which are lower than existing state-of-the-art hardening methods.

## Key Takeaways
- Standard Split Computing is highly vulnerable to hardware bit-flips in the Head model, which can corrupt the entire inference chain.
- Bounding activation functions and feature map distributions is an effective, low-cost way to mask hardware faults.
- Retraining the model to adapt to these new bounds is crucial for maintaining high accuracy while increasing robustness.
- These techniques are scalable and highly suitable for real-time, safety-critical vision tasks where hardware redundancy is too expensive.

#toread #edge-computing #split-computing #iot
