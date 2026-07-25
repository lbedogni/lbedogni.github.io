# SplitBeam: Effective and Efficient Beamforming in Wi-Fi Networks Through Split Computing

**Authors:** Niloofar Bahadori, et al.
**URL:** https://arxiv.org/abs/2310.08656

## Summary
SplitBeam is an IEEE 802.11 standard-compliant framework that applies split computing to optimize beamforming in Wi-Fi 6/7 networks. In standard MIMO beamforming, Stations (STAs) must perform computationally expensive Singular Value Decomposition (SVD) and Givens Rotation (GR) to calculate Beamforming Matrices (BM), and then transmit large feedback reports to the Access Point (AP), consuming significant airtime. SplitBeam replaces this with a DNN split: a **Head Model** on the STA generates a highly compressed representation of the BM from Channel State Information (CSI), and a **Tail Model** on the AP reconstructs the full matrix.

## Analysis of Results
Evaluated using real-world CSI data and FPGA hardware synthesis, SplitBeam achieved:
- **Computational Efficiency:** Reduced the computational load on STAs by up to **84%** compared to the 802.11 standard and **89%** compared to previous DNN-based methods.
- **Overhead Reduction:** Reduced the airtime overhead/feedback size by up to **81%**, which is critical for reducing congestion in high-density Wi-Fi 7 environments.
- **Performance & Latency:** Maintained a Bit Error Rate (BER) within $10^{-3}$ of standard approaches. FPGA results showed an end-to-end reporting delay of **<7ms**, fitting within the critical 10ms coherence time required for MU-MIMO.
- **Generalization:** The model remained robust across different physical environments, demonstrating that the learned mapping from CSI to BM generalizes well.

## Key Takeaways
- Split computing can be successfully applied to the **Physical Layer (PHY)** of wireless communication to optimize network protocols.
- The "Bottleneck Optimization Problem" (BOP) allows for a tunable trade-off between accuracy, computational complexity, and communication overhead.
- Reducing feedback size and computation on the STA not only saves battery life but also increases the overall spectral efficiency of the wireless network.

#toread #edge-computing #split-computing #iot
