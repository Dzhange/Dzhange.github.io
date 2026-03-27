---
title: "StrobeNet: Category-Level Multiview Reconstruction of Articulated Objects"
collection: projects
permalink: /projects/StrobeNet
excerpt: 'Category-level 3D reconstruction of articulated objects from one or more RGB images via articulation canonicalization.'
thumbnail: strobenet_teaser.png
date: 2020-12-1
# venue: 'Journal 1'
# paperurl: 'None'

# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
StrobeNet addresses category-level 3D reconstruction of articulated objects from one or more RGB images. Reconstructing general articulated object categories is challenging due to wide variation in shape, appearance, and topology across instances and articulation states.

Our key idea is **articulation canonicalization**: mapping object observations to a canonical articulation state, enabling correspondence-free multiview aggregation. An end-to-end trainable network estimates feature-enriched canonical 3D point clouds, articulation joints, and part segmentations from input images. These intermediate representations are then used to generate an implicit function for final shape reconstruction.

StrobeNet can reconstruct objects observed in different articulation states across images with large baselines, and produces animatable 3D models. Evaluations on our benchmark dataset demonstrate high reconstruction accuracy that improves as more views are added.

![StrobeNet overview](../images/strobenet_teaser.png)

[Project website](https://dzhange.github.io/StrobeNet/)
