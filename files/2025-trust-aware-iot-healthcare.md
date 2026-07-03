# AI-embedded IoT healthcare optimization with trust-aware mobile edge computing

- **Source**: [Nature Scientific Reports](https://www.nature.com/articles/s41598-025-29370-y)
- **Date**: December 2025
- **Field**: IoT, Mobile Edge Computing (MEC), Trust-aware Systems

## Summary
The paper introduces the **ECTI model**, a framework designed to optimize IoT-enabled healthcare systems by integrating AI-driven decision-making with trust-aware routing.

### Key Mechanism
- **Hybrid Trust Model**:
  - **Direct Trust**: Based on successful/failed interactions.
  - **Indirect Trust**: Based on weighted neighbor feedback.
  - **ML-based Anomaly Detection**: Uses a Random Forest classifier to predict malicious behavior and adjust the trust score.
- **Adaptive Security**: Implements an adaptive encryption strength ($S_{enc}$) where lower-trusted devices are subjected to stronger encryption to protect data integrity.
- **Temporal Decay**: Applies a decay factor $\lambda$ to prioritize recent device behavior over old history.

## Analysis & Results
- **Security**: Mitigates malicious threats and data breaches in heterogeneous IoT environments.
- **Reliability**: Ensures patient data consistency and efficient resource utilization through a trust-adjusted ML score.
- **Impact**: Provides a scalable approach to secure, real-time health monitoring in smart cities.

## Relevance to Luca's Research
Relevant to **IoT** and **Edge Computing**. While not focusing on "Split Computing" per se, it addresses the *reliability* and *security* aspects of the distributed edge infrastructure, which are critical for deploying split inference in sensitive domains like healthcare.
