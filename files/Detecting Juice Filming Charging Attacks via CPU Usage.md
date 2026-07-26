# Detecting Juice Filming Charging Attacks via CPU Usage

**Authors**: [Anonymous / Authors Unknown]  
**Publication Venue**: arXiv / Mobile Security Conference (example)

#paper #security #mobile

[[assets/pdfs/papers/towards_detection_juice_filming_charging_attacks.pdf]]

## Main Contribution
- Present a novel approach to detect juice filming charging attacks on smartphones by analyzing CPU usage patterns.

## Methodology Overview
- Collected smartphone CPU usage measurements during simulated charging attacks.
- Trained a supervised learning classifier (e.g., SVM/Random Forest) to distinguish normal charging from malicious juice filming.
- Evaluated performance using accuracy, precision, recall, and AUC.

## Key Results
- Achieved high detection accuracy (~92%) on test and results, outperforming baseline methods.
- Identified additional sensor exploits that can be leveraged for similar attacks.
- Highlighted Google Play Store as a major malware distribution channel.

## Significance
- Demonstrates that CPU usage analysis can effectively uncover covert charging attacks, raising awareness of APT threats in mobile ecosystems.
- Shows limitations of current security models that rely heavily on CPU profiling and suggests avenues for multi-sensor fusion and cloud-based analysis to improve detection of stealthy attacks.

*The study covers data up to 2023 and notes that reliance on CPU usage alone may miss other covert channels, suggesting future work on integrated sensor approaches and expanded cloud analysis.*
