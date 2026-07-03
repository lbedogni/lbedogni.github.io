# A novel middleware for adaptive and efficient split computing for real-time object detection

**Authors:** Matteo Mendula, Paolo Bellavista, Marco Levorato, Sharon Ladron de Guevara Contreras
**URL:** https://www.sciencedirect.com/science/article/pii/S1574119225000173

## Summary
This paper presents **Furcifer**, a proactive, context-aware middleware designed to optimize real-time object detection on mobile devices. Instead of relying on a single computing paradigm, Furcifer dynamically switches between **Local Computing (LC)**, **Edge Computing (EC)**, and **Split Computing (SC)** based on real-time environmental conditions. It utilizes a "Pareidolic Policy Manager" powered by LSTMs to forecast network quality and server load, allowing the system to switch modes proactively *before* a connection failure occurs, thereby minimizing frame loss and latency.

## Analysis of Results
Evaluated across 250 indoor and outdoor experiments, Furcifer demonstrated substantial gains:
- **Efficiency Gains:** In moderate scenarios, it achieved a **2x reduction in energy consumption** and a **three-fold increase in FPS** compared to local computing, while increasing mean Average Precision (mAP) by **30%**.
- **Robustness in Dynamic Settings:** In unstable network conditions, Furcifer preserved **30% more energy** and maintained **16% higher accuracy** than static local computing. It completed **80% more frame inferences** than reactive strategies.
- **SC Engine Performance:** The specialized FP16 encoder produced a highly compressed latent space (0.0194 MB), reducing edge server GPU utilization by **25%** and power consumption by **20%** compared to standard edge offloading.

## Key Takeaways
- **Proactive Forecasting:** Switching computing modes based on predicted trends (proactive) is vastly superior to switching after a failure (reactive) for real-time vision tasks.
- **Hybrid Paradigms:** The ability to pivot between LC, EC, and SC allows an application to remain functional and efficient regardless of user density or network volatility.
- **Specialized Compression:** Custom SC encoders outperform general-purpose image compression in preserving the semantic information needed for high-accuracy object detection.

#toread #edge-computing #split-computing #iot
