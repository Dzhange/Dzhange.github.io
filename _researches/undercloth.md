---
title: "Towards 3D Human Shape Recovery Under Clothing"
collection: projects
permalink: /projects/shaper_under_cloth
excerpt: 'A learning-based method for estimating clothing fitness and recovering human body shape from clothed 3D scans.'
thumbnail: tightcap.png
date: 2019-3-1
# venue: 'Journal 1'
# paperurl: 'None'

# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
We present a learning-based method for estimating clothing fitness and recovering the underlying human body shape from clothed 3D scans.

Our approach maps clothed human geometry to a geometry image (clothed-GI). To achieve reliable alignment across different clothing types, we extend the parametric human model with skeleton detection and warping. For each pixel on the clothed-GI, we extract a multi-channel feature vector (color, position, normal) and train a modified conditional GAN for per-pixel fitness prediction on a comprehensive 3D clothing dataset.

Our technique significantly improves body shape prediction accuracy, particularly under loose and fitted clothing. We further demonstrate applications in human/clothing segmentation and virtual try-on with high visual fidelity.

[Paper](https://arxiv.org/pdf/1904.02601v1.pdf) ·
[Revised version](https://arxiv.org/pdf/1904.02601.pdf)