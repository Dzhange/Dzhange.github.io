---
title: "From 2,000 Labels to 200k Picks: Deploying Learned Visuomotor Policies at Righthand Robotics"
collection: projects
permalink: /projects/righthand-robotics
excerpt: 'How we replaced a rule-based picking heuristic with a learned visuomotor policy and scaled it to production.'
date: 2024-07-01
---

At [Righthand Robotics](https://righthandrobotics.com/), I worked on bringing learned visuomotor policies into production for warehouse piece-picking.

When I joined, the picking system relied on a rule-based centroid heuristic to select suction targets. It worked reasonably well on easy cases, but struggled with cluttered bins and irregular objects. We wanted to replace it with a learned policy that could predict both suction points and approach angles directly from RGB-D images.

The challenge was bootstrapping. We started by collecting around 2,000 human-labeled picks—annotators marking optimal grasp points on real production images. This gave us enough signal to train an initial model that could outperform the heuristic on corner cases.

Once we had a policy robust enough for deployment, the real iteration began. Every pick in production generated data: RGB-D observations, predicted targets, and binary success outcomes. We built tooling to ingest this stream and constructed a dataset that eventually grew to over 200k missions. With this "in-the-wild" data, we could continuously retrain and improve the model, catching failure modes that would have been impossible to anticipate in a lab setting.

The final system improved pick success by 8% on the difficult cases that had previously required manual intervention.
