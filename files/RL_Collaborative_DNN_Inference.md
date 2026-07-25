# Reinforcement Learning based collaborative DNN inference for edge intelligence

## Summary
This research proposes a framework for collaborative Deep Neural Network (DNN) inference in AIoT environments. Instead of executing a model on a single device or offloading it entirely to the cloud, it deploys multiple collaborative models across edge devices and servers.

## Key Contributions
- **RL Orchestration**: Uses a Reinforcement Learning (RL) solution to dynamically orchestrate the interaction and task offloading between collaborative models.
- **Adaptability**: The system adapts to real-time system dynamics, such as fluctuating wireless IoT link quality and device availability.
- **Efficiency**: Aims to balance the trade-off between inference accuracy, latency, and energy consumption.

## Analysis & Relevance
This work is a prime example of **Split Computing** and **Distributed Edge Inference**. The use of RL for orchestration is critical because edge environments are inherently stochastic. By dynamically adjusting how the DNN is executed across the collaboration, it ensures robustness that static partitioning cannot provide.

**Tags**: #AIoT #ReinforcementLearning #SplitComputing #EdgeIntelligence
