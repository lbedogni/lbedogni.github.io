# AUGUSTE: Online-Learning dApp for Predictive URLLC Scheduling

- **Author(s)**: Maxime Elkael, Michele Polese, Yunseong Lee, Koichiro Furueda, Tommaso Melodia
- **ArXiv Link**: [http://arxiv.org/abs/2606.03664v1](http://arxiv.org/abs/2606.03664v1)
- **Published**: 2026-06-02
- **Categories**: `cs.NI` (Networking and Internet Architecture), `cs.AI` (Artificial Intelligence)

## Abstract
Ultra Reliable and Low Latency Communications (URLLC) was one of the main motivations behind 5G, with 3GPP advertising 1-10 ms latency targets for applications such as industrial automation, Vehicle-To-Everything (V2X), tactical edge networking, and unmanned-system control. Years on, real 5G Time Division Duplexing (TDD) networks still show median Uplink (UL) round-trip times in the 50-70 ms range, largely because of the Scheduling Request (SR) procedure that a User Equipment (UE) must complete before transmitting UL data. Existing remedies, primarily Configured Grant (CG) scheduling, only eliminate this overhead for strictly periodic traffic and require cross-layer synchronization, which has limited their adoption. 

We propose AUGUSTE (Anticipatory Uplink Grants for URLLC via Self-Adapting Temporal Estimation), a learning-based Medium Access Control (MAC) scheduling framework that embeds online Machine Learning (ML) models in the UL scheduler to predict packet arrivals and proactively allocate resources before an SR is issued. An adaptive state machine alternates between a learning phase that collects unbiased arrival statistics and a confident phase that exploits the learned predictions to schedule only when traffic is expected. We evaluate AUGUSTE on a real 5G testbed running OpenAirInterface across three URLLC traffic patterns (request-response, ML edge inference, and periodic autonomous reporting), and show that it operates at the best achievable point on the latency-overhead trade-off: it matches always-on scheduling's median Round Trip Time (RTT) (around 10 ms, halving the 20 ms SR-based baseline) at roughly one-tenth its resource cost (7-10 percent overhead).

## Analysis & Relevance to Luca's Field
* **Core Idea**: AUGUSTE tackles a key edge latency bottleneck—the scheduling request (SR) handshake in cellular uplinks. By incorporating online machine learning within the gNodeB MAC scheduler to predict packet arrivals, it proactively allocates uplink grants.
* **Connection to IoT/Edge Inference**: Modern distributed edge inference systems suffer from uplink latency spikes when sending intermediate feature representations (e.g., in split computing) or raw sensor data to edge servers. AUGUSTE's predictive uplink scheduling reduces uplink latency to 10 ms (matching always-on performance) with minimal overhead, directly optimizing the network fabric supporting real-time Edge AI.
* **Evaluation**: Real-world validation on an OpenAirInterface 5G testbed using representative ML edge inference traffic patterns makes this paper highly practical and impactful.
