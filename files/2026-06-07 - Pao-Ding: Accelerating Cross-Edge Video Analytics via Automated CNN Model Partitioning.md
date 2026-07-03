# Pao-Ding: Accelerating Cross-Edge Video Analytics via Automated CNN Model Partitioning

**Authors:** Liang, et al.
**URL:** https://ieeexplore.ieee.org/document/11195759

## Summary
Pao-Ding is a framework designed to accelerate cross-edge video analytics by enabling collaborative processing among multiple edge devices. Unlike many existing split computing methods that only support simple linear model chains, Pao-Ding employs gradient information to automatically parse the structure of Convolutional Neural Network (CNN) models. This allows it to effectively partition chain models, simple Directed Acyclic Graphs (DAGs), and even complex DAG models. Additionally, Pao-Ding incorporates a layer-pruning-based algorithm to further reduce the computational overhead of the partitioned sub-models.

## Analysis of Results
By automating the parsing of CNN structures, Pao-Ding enables the deployment of more complex and accurate architectures across a distributed edge environment. The integration of layer pruning significantly reduces the compute and memory requirements on each edge node, allowing for higher frame rates in real-time video analytics without sacrificing significant accuracy. The framework proves that automated structure parsing is a scalable way to handle the diversity of modern CNN architectures in collaborative edge computing.

## Key Takeaways
- Moving beyond simple chain partitioning to DAG-based partitioning is essential for supporting modern, complex CNN architectures on the edge.
- Using gradient information for automatic model parsing removes the need for manual, expert-driven split point selection.
- The combination of structural partitioning and layer pruning provides a synergistic effect, maximizing the throughput of cross-edge video analytics.

#toread #edge-computing #split-computing #iot
