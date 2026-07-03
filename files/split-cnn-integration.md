# Coderef-monorepo: Split CNN Inference Integration

## 📍 Project Context
This document captures knowledge from the [Split CNN Inference paper (arXiv:2605.09357)](https://arxiv.org/abs/2605.09357) and how it applies to our Edge Computing framework (coderef-monorepo).

### Key Components:
- **Control Plane**: Dashboard orchestration
- **Data Plane**: Execution Agents handling model parallelism
- **Common Kernel**: Shared tools/APIs

## 👇 Key Insights from arXiv:2605.09357
The paper solves the **peak RAM bottleneck** in TinyML through:

1. **Sub-layer granularity partitioning**
   - Splits computation at sub-layer boundaries (not just layers)
   - Mechanisms:
     - *Kernel-wise partitioning* (filter/kernel-based)
     - *Neuron-wise partitioning* (output neuron-based)

2. **Resource Distribution**
   - Distributes both model parameters and intermediate activations

3. **Lightweight Orchestration**
   - Coordinator managing heterogeneous MCU resources
   - Maintains practical end-to-end latency

### Experimental Validation
- Successfully ran MobileNetV2 across 8 MCUs
- 70% reduction in per-MCU RAM usage
- Maintained real-time inference latency

## 📘 Obsidian Integration & Workflow
### Vault Setup
- Git-synced vault: `~/Documents/Obsidian Vault`
- Critical: ALWAYS commit/push after edits
- yml pitfalls:
  - Use `tags: [value1, value2]` instead of `tags: - value`
  - Autofix via `references/yaml-tag-fix.md` logic

### Maintenance Best Practices
1. Conduct coherence passes:
   - Audit folder structure
   - Consolidate silos
   - Schema alignment via front-matter inference
2. Entity discovery:
   - Create pages for unused wikilinks
3. Structural linking:
   - Regenerate index
   - Build Maps of Content

## 🤔 Implementation Roadmap
1. Analyze [split-mcus GitHub repo](https://github.com/shashsuresh/split-inference-on-MCUs) for implementation
2. Update Execution Agent specs to support sub-layer splitting
3. Develop orchestrator prototype (Control Plane)
4. Test with [MobileNetV2 implementation](https://github.com/shashsuresh/split-inference-on-MCUs)

## 💤 Next Steps
- Sync with hardware team to validate MCU hardware support
- Partner with kernel developers for sub-layer partitioner
- Schedule proof-of-concept with MobileNetV2 model
