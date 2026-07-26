**Pruning-Based Network Partitioning**

- Description: Neural network pruning that leaves some network partitions separable - each partition can be computed independently on different devices and later recombined
- Key Question: Is this actually feasible? Need to investigate with Cavicchioli
- Potential Advantage: Dynamic network decomposition based on pruning patterns


**Research Questions:**
- Which pruning techniques preserve partitionability?
- How to identify recombinable partitions post-pruning?
- Communication overhead vs. computation distribution trade-off

**Follow-up:**
- Contact: Cavicchioli (check existing notes for context)