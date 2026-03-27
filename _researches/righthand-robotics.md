---
title: "Learned Visuomotor Picking in Production"
collection: projects
permalink: /projects/righthand-robotics
excerpt: 'Replaced a rule-based picking heuristic with a learned visuomotor policy, scaling from 2,000 labeled examples to a continuously improving production system.'
date: 2024-07-01
---

At [Righthand Robotics](https://righthandrobotics.com/), I led the development of learned visuomotor policies for warehouse piece-picking, replacing the existing rule-based system with a data-driven approach.

**The problem.** The production picking system used a centroid-based heuristic to select suction targets. While adequate for simple cases, it struggled with cluttered bins and irregular objects. We set out to replace it with a learned policy that predicts both suction points and approach angles directly from RGB-D images.

**Bootstrapping from scratch.** We collected approximately 2,000 human-labeled picks—annotators marking optimal grasp points on real production images. This initial dataset was sufficient to train a model that outperformed the heuristic on challenging cases.

**Scaling through deployment.** Once deployed, every production pick generated training data: RGB-D observations, predicted targets, and binary success outcomes. We built an automated data pipeline to ingest this stream, growing the dataset to over 200,000 missions. This continuous retraining loop surfaced failure modes that would have been impossible to anticipate in a lab setting.

**Results.** The learned system improved pick success rate by 8% on difficult cases that had previously required manual intervention.
