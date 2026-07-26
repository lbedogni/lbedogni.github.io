# Towards Energy-Efficient Split Computing: A Hardware-Software Co-Design
- **Source**: EuroSys 2025 (Poster)
- **Topic**: Split Computing / HW-SW Co-design
- **Key Idea**: A two-phase framework (Offline NSGA-III optimization + Online dynamic controller) that jointly optimizes split points and hardware settings (CPU frequency, TPU usage).
- **Results**:
    - Evaluated with VGG16 on Raspberry Pi 4B + Coral TPU.
    - Reduced latency QoS violations to 4% (from 25%).
    - Median energy consumption < 3J.
- **Significance**: Demonstrates that HW-SW co-optimization is critical for balancing energy and latency in real-time edge ML.
