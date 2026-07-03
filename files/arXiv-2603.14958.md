# [2603.14958] Lightweight User-Personalization Method for Closed Split Computing

**Date:** Mar 2026
**Field:** Split Computing, Model Adaptation, Privacy

## Summary
Introduces SALT (Split-Adaptive Lightweight Tuning), a framework for adapting "closed" split computing systems where the model's head and tail networks are frozen and inaccessible.

**Key Contributions:**
- **Compact Client-Side Adapter:** Refines intermediate representations produced by the frozen head, enabling adaptation without modifying the core networks.
- **Multi-Objective Adaptation:** Supports user personalization, communication robustness (e.g., high packet loss), and privacy-aware inference.
- **Efficiency:** Significantly reduces training latency (60%+) compared to conventional fine-tuning.

## Analysis
SALT addresses a very practical constraint: the "closed" nature of many deployed models. The ability to personalize and harden a model against noise/packet loss purely on the client side without increasing communication overhead is a major win for privacy and efficiency.

**Relevance to Luca:** High. Focuses on Split Computing and the practicalities of deployment.
