# DistrEE: Distributed Early Exit of Deep Neural Network Inference on Edge Devices

**Source**: [arXiv:2502.15735](https://arxiv.org/abs/2502.15735)
**Key Fields**: Distributed Inference, Edge Intelligence, Early Exit, NoNN

## Summary
DistrEE is a framework that integrates **model early exit** with **distributed inference**. It leverages the "Network of Neural Networks" (NoNN) approach, where a model is partitioned into independent student models across multiple devices. DistrEE adds early exit branches to these models to allow the system to terminate inference early for "simple" inputs.

## Analysis
By combining distributed processing with dynamic early exits, DistrEE optimizes the trade-off between accuracy and latency. It recognizes that not all data requires the full depth of a network. The joint training of these exit branches ensures that the collaborative system can adapt to both input difficulty and resource fluctuations.

## Relevance to Luca's Research
Relevant to **Distributed Edge Inference** and **IoT**, showcasing how adaptive computation (early exit) can be scaled across a distributed set of edge nodes.
