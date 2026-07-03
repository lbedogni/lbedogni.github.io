# InTec: Integrated Things-Edge Computing Framework

**Source:** Springer (Computing)
**Field:** IoT, Edge Computing, ML Pipeline Distribution

## Summary
InTec introduces a three-tier architecture (Things $\rightarrow$ Edge $\rightarrow$ Cloud) designed to strategically distribute ML pipelines. By processing data as early as possible (at the "Things" layer), the framework reduces the burden on the edge and cloud.

## Analysis
The framework provides strong empirical evidence for the benefits of a truly distributed ML pipeline. The results are impressive:
- **Response Time:** $\downarrow$ 81.56%
- **Network Traffic:** $\downarrow$ 10.92%
- **Edge Energy:** $\downarrow$ 21.86%
- **Cloud Energy:** $\downarrow$ 25.83%

This validates the hypothesis that pushing intelligence further toward the "extreme edge" (the Things layer) is more efficient than simple Edge-Cloud offloading. It's a benchmark for scalable and energy-efficient IoT applications.

**Key Takeaways:**
- Validates a 3-tier distribution model.
- Significant energy and latency gains.
- Practical application in human motion detection (MHEALTH dataset).
