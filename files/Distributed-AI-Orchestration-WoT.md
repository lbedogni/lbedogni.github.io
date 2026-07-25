# Distributed AI Orchestration in Web-of-Things for Accessible Indoor Assistance

**Source:** [DOI: 10.5220/0014955800004018](https://doi.org/10.5220/0014955800004018)
**Date:** 2026 (ICEIS 2026)
**Authors:** Seyed Shahabadin Nasabeh, Santiago Meliá, Jaume Aragonés, Barbara Leporini, Diana Gadzhimusieva

## Summary
This paper presents a **Web of Things (WoT)** based information system designed to assist visually impaired people (VIPs) with indoor mobility. The core innovation is a **Distributed AI Orchestrator (DAIO)** that coordinates multiple AI-based assistive capabilities (object detection, scene description, OCR, chatbot, color recognition, and IoT control) across a **cloud-edge continuum** (specifically, smartphones and cloud services).

The system uses the **MoSIoT framework**, which separates domain knowledge (reusable templates for patient profiles, devices, and care plans) from individual user configurations. The orchestrator dynamically allocates tasks between the edge and the cloud based on latency sensitivity, resource availability, and the user's specific accessibility profile.

## Analysis of Results
- **Orchestration Efficiency:** The study demonstrates that moving from fragmented, single-function apps to a unified, orchestrated architecture reduces the cognitive load on VIPs and provides a more continuous assistive experience.
- **User Acceptance (TAM):** Using the Technology Acceptance Model (TAM), the authors found that **perceived usefulness** and **perceived ease of use** are the primary drivers for adoption.
- **Distributed Execution:** The framework successfully proves that dynamically deciding where to execute AI functions (edge vs. cloud) preserves responsiveness and ensures the system remains accessible even under varying resource conditions.

## Key Takeaways for Research
- **Distributed AI Orchestration:** This is a practical application of "Distributed Edge Inference" where the "orchestrator" acts as the decision-maker for task offloading.
- **WoT Integration:** Using Web of Things standards allows for a modular and interoperable way to expose AI capabilities as services, which is a scalable approach for heterogeneous IoT environments.
- **Human-Centric Edge Computing:** The research highlights that for assistive technologies, the "optimal" split or allocation isn't just about latency/energy, but about the **user's perceived ease of use** and accessibility requirements.

#toread #edge-computing #distributed-ai #iot #web-of-things #accessibility
