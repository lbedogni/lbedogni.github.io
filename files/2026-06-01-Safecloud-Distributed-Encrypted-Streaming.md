# Safecloud: A Distributed, Encrypted Storage Cloud for Streaming

**Date:** 2026-06-01
**Field:** Distributed Systems, Edge Computing, Privacy

## Abstract
Safecloud is a distributed, encrypted, self-pricing storage and streaming network. It utilizes a decentralized architecture where storage and routing nodes (Drops and Jets) never see plaintext data. Files are split into encrypted chunks and distributed across browser tabs (Drops) and federated routing servers (Jets), with only the owner holding the keys.

## Analysis
While not a "Split Computing" paper in the sense of neural network partitioning, Safecloud represents the "Distributed Edge" philosophy. By leveraging browser tabs as storage nodes, it turns every user's client into a part of the infrastructure. This architecture is a precursor to more complex distributed inference tasks where model weights or intermediate features might be stored similarly.

## Key Takeaways
- High privacy: plaintext is never exposed to the infrastructure.
- Decentralized storage: utilizes IndexedDB in browser tabs for a massive, distributed "cloud".
- Self-pricing mechanism for incentive alignment in a federated network.
