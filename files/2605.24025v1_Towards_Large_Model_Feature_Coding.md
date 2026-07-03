# Towards Large Model Feature Coding (LaMoFC)

- **Title**: Towards Large Model Feature Coding
- **Authors**: Youwei Pang, Changsheng Gao, Dong Liu, Huchuan Lu, Weisi Lin
- **Date Found**: 2026-06-24
- **Published Date**: 2026-05-20 (arXiv:2605.24025v1)
- **Topics**: Split Computing, Feature Compression, Deep Learning, Edge Computing
- **Link**: [arXiv Abstract](https://arxiv.org/abs/2605.24025v1) | [PDF](https://arxiv.org/pdf/2605.24025v1)

---

## 📌 Summary & Core Contributions
*   **The Problem**: Split computing/execution alleviates computation and memory constraints on edge devices by partitioning a model across devices. However, this approach introduces heavy data transmission and storage overhead of intermediate features. Traditional feature coding mechanisms designed for CNNs (targeting homogeneous spatial activation maps) fail on modern Large Models (LMs). Large models generate *heterogeneous features* with varying statistical distributions and compression tolerances (e.g., multi-level/multi-modal representations and autoregressive context caches).
*   **The Proposed Solution**: Introduces **LaMoFC** (Large Model Feature Coding) as a fundamental system component. The authors present **LaMoFCBench**, a comprehensive evaluation benchmark for feature coding on large models.
*   **LaMoFCBench Dataset**: Covers 4 categories and 16 scenarios, integrating widely-adopted LLM/LMM architectures and multiple split-computing environments.
*   **Benchmark Findings**: Testing universal feature codecs reveals a major misalignment between existing compression/coding paradigms and the highly heterogeneous nature of modern large model intermediate features.

## 🔍 Critical Analysis & Relevance to Luca's Research
*   **Direct Alignment with Split Computing**: This paper is highly relevant to Luca's interest in Split Computing and Distributed Edge Inference. It addresses the exact bottleneck of split computing: transmission latency/overhead of intermediate feature maps.
*   **Shifting Paradigm**: Points out that CNN-centric feature coding doesn't work for transformer-based or multi-modal large model activations (especially with autoregressive KV caches), demanding a major shift in how feature compression is approached at the edge.
*   **Actionable Resource**: The release of `LaMoFCBench` (https://github.com/lartpang/LaMoFCBench) provides a concrete testbed for any future split-inference/split-computing protocols Luca might develop.
