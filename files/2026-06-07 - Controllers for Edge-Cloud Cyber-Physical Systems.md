# Controllers for Edge-Cloud Cyber-Physical Systems

**Authors:** Luigi Capogrosso, et al.
**URL:** https://ieeexplore.ieee.org/abstract/document/10885702

## Summary
This paper explores the trade-off between latency and accuracy in Cyber-Physical Systems (CPS) that utilize Deep Neural Networks (DNNs) for perception and control. To combat the resource limitations of edge devices and the high latency of the cloud, the authors propose a **Split Computing (SC) approach with Early Exit**. This system uses a "Head" DNN on the edge for a quick, coarse state estimate to trigger an immediate control action, followed by a "Tail" DNN on the cloud that provides a refined, high-accuracy estimate for subsequent corrections. The system's safety is measured by the size of the "reachable state space," with the goal of minimizing this space to ensure stability.

## Analysis of Results
Using an F1Tenth racing car state-space model, the researchers compared four scenarios:
- **Only Edge:** High uncertainty led to the largest reachable state space (51.10 / 229.94) and massive control effort (326.03), indicating high risk and low efficiency.
- **Only Cloud:** Better accuracy but high latency produced a reachable set of 28.05 / 106.28.
- **Naïve Split-Computing:** Combining both outperformed either individually.
- **Optimized Split-Computing:** Achieved the best results with a reachable state space of **20.33 / 73.65** and a minimal control effort of **31.05**, very close to the theoretical "ideal" behavior.

The results show that optimized resource distribution (balancing edge and cloud latency) is more effective than simply increasing the power of one side.

## Key Takeaways
- **Safety via Hybridization:** Early-exit split computing allows for immediate reaction times while maintaining long-term accuracy.
- **Energy Efficiency:** Lowering the control effort via better state estimation significantly reduces the energy requirements for the physical actuator.
- **Reachability Metric:** The size of the reachable state space is an excellent objective function for optimizing DNN partitioning and sizing in safety-critical IoT applications.

#toread #edge-computing #split-computing #iot
