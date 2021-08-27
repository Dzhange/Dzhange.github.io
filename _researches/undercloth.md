---
title: "Towards 3D Human Shape Recovery Under Clothing"
collection: projects
permalink: /projects/shaper_under_cloth
excerpt: 'We present a learning-based scheme for robustly and accurately estimating clothing fitness as well as the human
shape on clothed 3D human scans.'
date: 2019-3-1
# venue: 'Journal 1'
# paperurl: 'None'

# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
We present a learning-based scheme for robustly and accurately estimating clothing fitness as well as the human
shape on clothed 3D human scans. Our approach maps the clothed human geometry to a geometry image that we
call clothed-GI. To align clothed-GI under different clothing, we extend the parametric human model and employ
skeleton detection and warping for reliable alignment. For each pixel on the clothed-GI, we extract a feature vector
including color/texture, position, normal, etc. and train a modified conditional GAN network for per-pixel fitness prediction using a comprehensive 3D clothing. Our technique significantly improves the accuracy of human shape prediction, especially under loose and fitted clothing. We further demonstrate using our results for human/clothing segmentation and virtual clothes fitting at a high visual realism


Get the paper [Here](https://arxiv.org/pdf/1904.02601v1.pdf)

And its [revision](https://arxiv.org/pdf/1904.02601.pdf)