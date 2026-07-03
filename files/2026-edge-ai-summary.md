# Edge Computing & AI Advancements Summary (May 2026)

**Source:** SciPapermill / Various
**Date:** May 2026
**Field:** IoT, Edge Computing, AI/ML at the Edge

## Key Papers & Innovations

### 1. Efficient 3D Perception
- **Paper:** *ESAM++: Efficient Online 3D Perception on the Edge*
- **Innovation:** 3D Sparse Feature Pyramid Network (SFPN).
- **Impact:** 3x faster inference, 2x smaller models on mobile CPUs (iPhone 15); makes real-time 3D instance segmentation practical without GPUs.

### 2. Privacy & Federated Learning
- **Paper:** *SCALE: Sensitivity-Aware Federated Unlearning...*
- **Innovation:** Dual-level approach combining layer sensitivity analysis and AoI-driven adaptive sparsification.
- **Impact:** Precise removal of client data in MEC systems to ensure privacy compliance.

### 3. V2X Resource Allocation
- **Paper:** *Integrated Sensing, Communication, and Computing for NR-V2X...*
- **Innovation:** MAPPO-SPS (Multi-Agent Reinforcement Learning framework).
- **Impact:** Jointly optimizes sensing, communication, and computation in NR-V2X under decentralized operation.

### 4. Knowledge Distillation for Edge
- **Paper:** *SAM3-Assisted Training of Lightweight YOLO Models...*
- **Innovation:** Automated distillation pipeline using SAM 3 as a zero-shot auto-annotator.
- **Impact:** ~200x inference speedup for precision livestock monitoring.

### 5. Hardware Acceleration
- **Paper:** *XL-HD: Extended Learning in Hyperdimensional Computing...*
- **Innovation:** Deterministic projection-based HDC using Sobol sequences on ReRAM crossbars.
- **Impact:** Single-cycle inference with sub-μJ energy consumption.

### 6. Generative AI (AIGC) at the Edge
- **Innovations:** Game-theoretic MASL for scheduling and DSAC (Diffusion-based Soft Actor-Critic) for Tree-of-Thoughts reasoning.
- **Impact:** Significant reduction in service completion time for complex generative AI tasks on MEC.

### 7. Secure Distributed Computing
- **Paper:** *Secure and Parallel Determinant Computation (SPDC)*
- **Innovation:** Composite Element Distortion + Panth Rotation Theorem.
- **Impact:** Privacy-preserving matrix operations on untrusted edge servers with $O(n^2)$ complexity.

## Synthesis for Luca
The trend is clearly moving towards **specialized hardware (ReRAM)**, **foundation model distillation (SAM 3 $\to$ YOLO)**, and **sophisticated resource scheduling (MARL/Game Theory)** to handle the increasing complexity of LLMs and 3D perception at the edge.
