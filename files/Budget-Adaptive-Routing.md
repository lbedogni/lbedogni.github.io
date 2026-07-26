# Budget-Adaptive Routing: Skipping the Weak When the Strong Answers Anyway

## Abstract
Edge-cloud inference collaborations are often designed with a routing estimator that decides whether to offload each frame from weak models at the edge to stronger models in the cloud. Existing systems place the routing estimator after the weak detector, so the weak forward pass is always performed. This paper addresses this by proposing a budget-adaptive routing mechanism.

## Analysis
The paper provides a significant advancement in distributed edge inference by optimizing the trigger mechanism for offloading. By bypassing the weak model's inference when the outcome is predictable or when a strong cloud response is expected, it saves valuable compute resources and reduces total latency, directly addressing one of the core challenges in split computing and distributed edge-cloud collaboration.

## Fields
- Edge Computing
- Distributed Edge Inference
- Split Computing
