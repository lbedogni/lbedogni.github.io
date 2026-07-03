# Fast and fair split computing for accelerating deep neural network (DNN) inference

**Authors:** Dongju Cha, Jaewook Lee, Daeyoung Jung, Sangheon Pack
**URL:** https://www.sciencedirect.com/science/article/pii/S2405959524001164

## Summary
This paper focuses on the challenges of latency and resource equity in split computing for Deep Neural Networks (DNNs). Traditional split computing often suffers from long transmission times (when intermediate feature maps are large) and "unfairness," where resource-constrained or "selfish" mobile devices are unable to offload their tasks due to server saturation. To address this, the authors propose **Fast and Fair Split Computing (F2SC)**, a low-complexity heuristic algorithm that optimizes split points to accelerate inference while ensuring a fair distribution of edge server resources among all requesting devices.

## Analysis of Results
The F2SC algorithm was evaluated against conventional split computing approaches. The results indicate a significant improvement in performance:
- **Latency Reduction:** F2SC reduced overall inference time by **38% to 201%** compared to baseline methods.
- **Fairness:** The heuristic successfully balanced the workload, preventing a few "heavy" devices from monopolizing server resources and ensuring that all devices achieved acceptable performance targets.

## Key Takeaways
- In multi-user IoT environments, "fairness" in resource allocation is as important as raw speed to ensure system-wide reliability.
- Heuristic-based split point selection can effectively balance the trade-off between transmission latency and server-side processing time.
- F2SC provides a scalable way to implement split computing in crowded edge scenarios without requiring complex, high-overhead optimization solvers.

#toread #edge-computing #split-computing #iot
