---
layout: page
title: project 1
description: Segment Anything fine-tuned for ring segmentation
img: assets/img/projects/sam_rings/SAM.png
importance: 1
category: work
related_publications: true
---

This project tackles an issue about the segment anything model for segmenting rings and pairs of rings.
To solve this problem I used a LoRA on the attention module. The dataset is handmade with a few training sets.
I used the dice loss and the test set is based on this validation metric.
I tested different dimensions for the LoRA matrices.

You can find all the details in the README of the repository: https://github.com/MathieuNlp/Sam_LoRA