# Distributed Inference on Mobile Edge and Cloud: An Early Exit based Clustering Approach

- **Source**: [arXiv:2410.05338](https://arxiv.org/abs/2410.05338)
- **Date**: October 2024
- **Field**: Distributed Edge Inference, DNN Deployment

## Summary
The paper proposes **DIMEE**, a distributed inference framework that optimizes the placement of Deep Neural Network (DNN) layers across mobile, edge, and cloud tiers. 

### Key Mechanism
- **Tiered Deployment**: 
  - **Mobile**: Small-sized DNN (initial layers) for "easy" samples.
  - **Edge**: Medium-sized DNN for "moderate" complexity samples.
  - **Cloud**: Full-fledged DNN for "hard" samples.
- **Early Exit (EE)**: Uses EE strategies to dynamically decide the complexity of a sample and route it to the appropriate processing tier.
- **Cost Optimization**: Accounts for the offloading cost when moving data from mobile to edge/cloud.

## Analysis & Results
- **Efficiency**: Achieves a significant reduction in inference cost (**> 43%**) compared to cloud-only inference.
- **Accuracy**: Maintains high performance with a minimal accuracy drop (**< 0.3%**).
- **Significance**: Validates that early-exit based routing in a hierarchical (mobile $\rightarrow$ edge $\rightarrow$ cloud) setup can effectively balance latency and accuracy for NLP tasks (validated on GLUE datasets).

## Relevance to Luca's Research
Directly addresses **Distributed Edge Inference**. The use of early-exit mechanisms to partition the workload across the edge continuum is a core challenge in split computing and distributed AI.
