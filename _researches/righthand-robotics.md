---
title: "Visuomotor Picking at Righthand Robotics"
collection: projects
permalink: /projects/righthand-robotics
excerpt: 'Designed and deployed learned visuomotor picking policies for production warehouse automation.'
date: 2024-07-01
---

At [Righthand Robotics](https://righthandrobotics.com/), I worked on deploying machine learning for robotic piece-picking in warehouse automation.

**Visuomotor Policy Deployment**: Designed and deployed a learned visuomotor picking policy to production. Replaced a rule-based centroid heuristic with a deep learning model predicting suction targets and approach angles from RGB-D, improving pick success by 8% on corner cases.

**Production Data Ops**: Constructed a large-scale dataset of 200k missions from production logs, including object descriptions and end-effector poses. Built the "in-the-wild" data collection tools used to train robust manipulation models.

**Reliability Engineering**: Wrote production-quality unit tests to ensure model reliability. Implemented hybrid rule-based behaviors for precise placement and fault recovery to ensure system robustness.
