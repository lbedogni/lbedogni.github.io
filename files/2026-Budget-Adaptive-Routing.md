# Budget-Adaptive Routing: Skipping the Weak When the Strong Answers Anyway

**Status:** To Read
**Date Found:** 2026-07-01
**Field:** Distributed Edge Inference / Edge-Cloud Collaboration

## Abstract
Edge-cloud inference collaborations are often designed with a routing estimator that decides whether to offload each frame from weak models at the edge to stronger models in the cloud. Existing systems place the routing estimator after the weak detector, so the weak forward pass is always executed. This paper proposes a budget-adaptive routing mechanism to optimize this process.

## Initial Analysis
This paper addresses a critical inefficiency in the "cascade" or "routing" pattern of edge-cloud inference. By moving the routing decision *before* the weak model execution (or making it adaptive), it can significantly reduce edge compute and latency when the cloud is the inevitable target. This is highly relevant to Luca's work on Distributed Edge Inference.

## Tags
#DistributedEdgeInference #EdgeCloud #Routing #LatencyOptimization
