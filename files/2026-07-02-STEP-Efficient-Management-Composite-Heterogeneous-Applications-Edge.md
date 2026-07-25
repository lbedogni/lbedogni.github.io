# Efficient Management of Composite Heterogeneous Applications at the Network Edge

**Authors**: Madhura Adeppady, Yenchia Yu, Ali Rahmanian, Ahmed Ali-Eldin Hassan, Carla Fabiana Chiasserini

**Published in**: IEEE Transactions on Network and Service Management (Early Access)

**Date of Publication**: 02 July 2026

**DOI**: [10.1109/TNSM.2026.3709656](https://doi.org/10.1109/TNSM.2026.3709656)

**Source**: IEEE Xplore - [Document 11593947](https://ieeexplore.ieee.org/abstract/document/11593947/)

---

## Abstract

Edge computing is a promising paradigm for deploying latency-sensitive applications (Apps) as it brings resources closer to end users. Edge Apps often adopt a microservice (MS) architecture, breaking monolithic Apps into lightweight, containerized MSs that can be dynamically and independently deployed. However, managing such Apps involves three key challenges: (i) optimizing the placement of MSs to reduce both response time and resource overhead, (ii) handling MS migration or relocation as users move while minimizing App service disruption (App downtime), and (iii) enabling MS sharing across Apps while ensuring performance guarantees. We formulate this as an optimization problem, named Multi-microservice Application Placement (MAP), prove its NP-hardness, and introduce STEP (State and Topology-aware Edge-MS Placement), a polynomial-time heuristic. STEP distinguishes itself from prior work by: (i) jointly considering stateful and stateless MS characteristics in deployment decisions, (ii) exploiting MS shareability to reduce resource usage, (iii) balancing response latency, App downtime, and resource utilization, and (iv) leveraging multiple versions of the same MS to adapt quality of service to available edge resources. Our results in a small-scale scenario show that STEP achieves near-optimal performance with only 7% higher CPU cost than the optimal solution. Large-scale real-time experiments on a Kubernetes cluster demonstrate that STEP consistently outperforms competing methods, achieving up to 50% lower deployment costs while delivering 50% gain in app quality and saving 15% in radio resources with over 90% request success rates.

---

## Key Contributions

1. **MAP Problem Formulation**: Multi-microservice Application Placement problem formalized and proven NP-hard
2. **STEP Heuristic**: State and Topology-aware Edge-MS Placement - polynomial-time algorithm
3. **Joint Stateful/Stateless Consideration**: Handles both stateful and stateless microservice characteristics
4. **MS Shareability Exploitation**: Reduces resource usage through microservice sharing across applications
5. **Multi-objective Optimization**: Balances response latency, App downtime, and resource utilization
6. **Multiple MS Versions**: Adapts QoS to available edge resources
7. **Experimental Validation**: Near-optimal (7% overhead) in small-scale; 50% lower costs, 50% app quality gain, 15% radio savings, 90%+ success rate in large-scale Kubernetes experiments

---

## Keywords

Edge Computing, Microservices, Application Placement, Resource Management, Kubernetes, QoS, Migration, Microservice Sharing

---

## Notes for Review

- [ ] Read full paper
- [ ] Extract methodology details for STEP heuristic
- [ ] Compare with other placement algorithms (e.g., [related papers in toread])
- [ ] Note experimental setup (Kubernetes cluster, real-time)
- [ ] Consider relevance to SCIoT framework and split computing survey

---

## Related Papers in TOREAD

- [[files/2026-06-07 - Request Deadline Split and Interference-Aware Request Migration in Edge Cloud.md]]
- [[files/2026-06-08-predictive-autoscaling-cloud-edge.md]]
- [[files/2026-06-08-terastal-dnn-scheduling.md]]
- [[files/Serverless Edge Computing Taxonomy.md]]
- [[files/2026-07-04-cloud-edge-end-collaborative-computing.md]]