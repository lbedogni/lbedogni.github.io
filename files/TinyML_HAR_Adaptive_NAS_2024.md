# TinyML-HAR: Ultra-Low-Power Human Activity Recognition Using Adaptive Neural Architecture Search
- **Source:** [arXiv:2408.06789](https://arxiv.org/abs/2408.06789)
- **Date:** August 2024
- **Field:** TinyML, Human Activity Recognition, Neural Architecture Search

## Summary
This paper introduces TinyML-HAR, a framework that combines neural architecture search (NAS) with domain-specific constraints for human activity recognition on microcontrollers. The approach optimizes for both accuracy and power consumption under strict memory (<256KB RAM) and latency (<50ms inference) constraints typical of wearable IoT devices. The method uses a multi-objective optimization strategy that considers sensor modality characteristics and activity transition patterns.

## Key Contributions
1. **Domain-Specific NAS Space:** Defines a search space optimized for temporal sensor data from accelerometers, gyroscopes, and IMUs, including specialized temporal convolution and attention modules.
2. **Multi-Objective Optimization:** Jointly optimizes accuracy, power consumption, memory footprint, and inference latency using a novel reward function that weights these factors based on deployment scenarios.
3. **Adaptive Sensor Fusion:** Includes a lightweight mechanism for dynamically weighting sensor modalities based on signal quality and activity type, improving robustness to sensor noise and placement variations.
4. **Hardware-Aware Quantization:** Implements mixed-precision quantization that preserves critical feature representations while minimizing memory and computational overhead.
5. **Open-Source Benchmark Suite:** Provides a standardized evaluation framework for comparing TinyML-HAR approaches across common HAR datasets (UCI-HAR, HHAR, PAMAP2, etc.).

## Analysis & Relevance
Highly relevant to Luca's work in [[Wearable Sensing]] and [[Human Activity Recognition]]. This paper addresses the core challenge of deploying accurate HAR models on resource-constrained edge devices, which is central to projects like the [[MASA Research Summary]] and [[IoT - ESP32 With Edge Impulse]]. The adaptive sensor fusion approach complements existing work in [[MobHAR]] and [[Self Supervised Learning]] for wearable systems. The benchmark suite could be valuable for validating [[Activity recognition - Benchmark]] and [[Activity recognition - Bicycles determine the road condition]] studies.

## Results
- Achieves 92.3% average accuracy on UCI-HAR dataset with 28.7KB RAM and 3.2mW average power consumption
- Outperforms MobileNetV3 and TinyNAS baselines by 4.7% accuracy while using 60% less energy
- Adaptive sensor fusion improves robustness to sensor placement errors by 35% compared to fixed-weight approaches
- Inference latency of 42ms on ARM Cortex-M4F @ 80MHz meets real-time requirements for most HAR applications