---
layout: page
title: AOI
permalink: /aoi
description: Automated Optical Inspection
img:
importance: 4
category: private-project
---

The objective of the Automated Optical Inspection (AOI) project is to determine any anomaly on a TFT screen of various sizes (from 7 inches up to 21). The solution we have adopted employs auto-encoders run on specific Intel hardware (Intel Movidius Compute stick), to analyze and identify any possible defect. We collect images from a digital linear 4K camera, and compare those images against a pre-trained model to identify differences. The output of the work is then fed to an operator, which can decide whether to pass or block the TFT.

At <a href="https://www.intel.co.uk/content/www/uk/en/customer-spotlight/stories/exor-customer-story.html">this link</a> you can see a video of what we developed together with other technologies part of the project.