# Split Computing for Mobile Devices: Energy and Latency Perspective

**Link:** [IEEE Explore](https://ieeexplore.ieee.org/document/10978101)
**Tags:** #SplitComputing #MobileEdge #EnergyEfficiency #LatencyOptimization

## Summary
This paper addresses the trade-off between inference latency and energy consumption in split computing for mobile devices. While most schemes optimize one or the other, this work proposes a joint optimization problem to minimize both.

## Key Analysis
- **Problem:** The difficulty of running sophisticated DNNs on mobile devices and the challenge of simultaneously optimizing energy and latency.
- **Innovation:** Incorporates "queue clearance latency" into the analysis, which provides a more realistic view of systems generating continuous inferences.
- **Outcome:** A framework for offloading computations to edge servers that balances the energy-latency trade-off.
- **Relevance to Luca:** Important for the **IoT** and **Edge Computing** aspects of his research, specifically regarding the practical constraints of mobile hardware and real-time processing requirements.

## To-Read Notes
- Analyze the mathematical formulation of the joint optimization problem.
- Examine how "queue clearance latency" is modeled and its impact on the results.
- Compare the proposed approach with current industry standards for model offloading.
