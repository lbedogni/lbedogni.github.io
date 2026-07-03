---
type: paper
tags: [WoT, Distributed-AI, Accessibility, Orchestration, MoSIoT, TAM]
url: https://www.researchgate.net/profile/Shahab-Nasabeh/publication/405355763_Distributed_AI_Orchestration_in_Web-of-Things_for_Accessible_Indoor_Assistance/links/6a178c2063540127809f9d80/Distributed-AI-Orchestration-in-Web-of-Things-for-Accessible-Indoor-Assistance.pdf
date_added: 2026-06-05
---
# Distributed AI Orchestration in Web-of-Things for Accessible Indoor Assistance

## Summary
This paper proposes a Web of Things (WoT)-based information system featuring a **Distributed AI Orchestrator (DAIO)** designed to provide low-latency, context-aware indoor assistance for visually impaired people (VIPs). Using the **MoSIoT (Modeling Scenarios of the Internet of Things)** framework, the system coordinates six AI-based assistive capabilities (object detection, scene description, OCR, chatbot, color recognition, and IoT control) across edge smartphones and cloud services.

The core innovation is the transition from fragmented, single-function tools to an integrated assistive ecosystem where user intents trigger coordinated service activation. Task allocation is dynamically managed between edge and cloud based on latency sensitivity, computational complexity, and accessibility requirements.

## Key Contributions
- **Orchestration-Centered Architecture:** Unifies heterogeneous AI capabilities as interoperable WoT services rather than isolated tools.
- **Intent-Driven Distributed Orchestration:** Dynamically allocates tasks between edge and cloud resources based on contextual conditions and user accessibility profiles.
- **User-Centered Validation:** Uses the **Technology Acceptance Model (TAM)** to show that perceived usefulness (PU) and perceived ease of use (PEOU) are the primary drivers for adoption among VIPs.

## Technical Details
- **Framework:** MoSIoT (model-driven approach).
- **Core Components:** 
    - **Admin/Domain Model:** Defines Patient Profiles, Device Templates, and Care Plan Templates.
    - **AI Orchestrator:** Mediates human-AI-environment interaction; uses BERT for intent classification and RAG (Retrieval-Augmented Generation) for complex context-aware responses.
    - **User App:** Integrates the six AI functions and monitors vitals via wearables.
- **Infrastructure:** Integration with Azure IoT Central for telemetry and monitoring.

## Evaluation Results (TAM)
- **Drivers:** Strong positive correlation between Behavioral Intention (BI) and both Perceived Usefulness (PU) and Perceived Ease of Use (PEOU).
- **Barriers:** Perceived External Control (PEC) — including privacy concerns and infrastructure limits — significantly negatively impacts the intention to adopt.
- **Insight:** Everyday usability and independence are stronger motivators than professional or job-related relevance.

## Links
- [Paper PDF](https://www.researchgate.net/profile/Shahab-Nasabeh/publication/405355763_Distributed_AI_Orchestration_in_Web-of-Things_for_Accessible_Indoor_Assistance/links/6a178c2063540127809f9d80/Distributed-AI-Orchestration-in-Web-of-Things-for-Accessible-Indoor-Assistance.pdf)
- [ResearchGate Publication Page](https://www.researchgate.net/publication/405355763_Distributed_AI_Orchestration_in_Web-of-Things_for_Accessible_Indoor_Assistance)

## Notes
- Analysis updated on 2026-06-05 using full PDF content.
