# ModalNet: Adaptive Modalities Selection for Energy-Efficient Multimodal Edge Sensing
- **Source:** [arXiv:2411.02468](https://arxiv.org/abs/2411.02468)
- **Date:** November 2024
- **Field:** Multimodal Sensing, Edge Computing, Adaptive Systems

## Summary
ModalNet presents a dynamic modality selection framework for multimodal edge sensing systems that automatically activates/deactivates sensors based on contextual relevance and energy constraints. The approach uses a lightweight meta-controller trained via reinforcement learning to optimize the trade-off between sensing completeness and battery life. Unlike fixed polling or simple threshold-based methods, ModalNet learns complex patterns of sensor usefulness across different activities, environments, and device states.

## Key Contributions
1. **Energy-Aware Meta-Controller:** A tiny neural network (<10KB) that predicts the information gain and energy cost of each sensor modality, making activation decisions every 100ms-1s depending on application requirements.
2. **Contextual Reward Function:** Incorporates activity recognition accuracy, environmental awareness needs, and user interaction patterns into the optimization objective, not just raw sensor data quality.
3. **Transfer Learning Across Devices:** Demonstrates that policies learned on one device configuration can be adapted to new sensor sets with minimal retraining, reducing deployment friction.
4. **Failure-Mode Awareness:** Explicitly models sensor degradation and intermittent connectivity, enabling graceful degradation rather than system failure when individual sensors malfunction.
5. **Real-World Validation:** Tested on three heterogeneous wearable platforms with 5-7 concurrent sensors over 2-week deployment periods in free-living conditions.

## Analysis & Relevance
This work extends Luca's existing interests in [[Edge Sensing as a Service]] and [[Wearable Sensing]] by addressing the \"always-on\" sensing dilemma in multimodal wearable systems. The adaptive activation strategy could significantly enhance projects like [[Activity Recognition - Text and Drive]] and [[Crowdsensing - Comunichiamo text.md]] by extending battery life without sacrificing data quality. The transfer learning approach is particularly relevant for [[Industry Collaborations]] where device heterogeneity is common. ModalNet's failure-mode handling connects well with reliability concerns in [[Industrial IoT]] applications referenced in [[Industry - Data digitalization]].

## Results
- Reduces average energy consumption by 47-63% compared to always-on multimodal sensing across three testbeds
- Maintains 91-95% of the accuracy achievable with continuous sensing for primary activity recognition tasks
- Adapts to sensor failures within 2-3 activation cycles, preserving 80%+ functionality with up to 40% sensor loss
- Transfer learning reduces retraining time by 70% when deploying to new hardware platforms with similar sensor modalities
- User studies show 38% preference for ModalNet-based systems due to noticeable battery life improvements without perceived loss of functionality