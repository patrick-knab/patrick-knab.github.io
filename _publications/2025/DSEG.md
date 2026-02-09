---
title:          "Beyond Pixels: Enhancing LIME with Hierarchical Features and Segmentation Foundation Models"
date:           2025-05-22 00:01:00 +0800
selected:       true
pub:            "International Conference on Learning Representations (ICLR) @ FM-Wild Workshop"
pub_date:       "2025"
abstract: >-
  LIME (Local Interpretable Model-agnostic Explanations) is a popular Interpretable AI framework for unraveling decision-making processes in vision machine-learning models. The technique utilizes image segmentation methods to identify fixed regions for calculating feature importance scores as explanations. Therefore, poor segmentation can weaken the explanation and reduce the importance of segments, ultimately affecting the overall clarity of interpretation. To address these challenges, we introduce the DSEG-LIME (Data-Driven Segmentation LIME) framework, featuring: i) a data-driven segmentation for human-recognized feature generation by foundation model integration, and ii) a user-steered granularity in the hierarchical segmentation procedure through composition. Our findings demonstrate that DSEG outperforms on several Interpretable AI metrics on pre-trained ImageNet models and improves the alignment of explanations with human-recognized concepts. The code is available under: https://github.com/patrick-knab/DSEG-LIME

cover:          /assets/images/covers/dseg.png

#cover:          /assets/images/covers/cover2.jpg
authors:
  - Patrick Knab
  - Sascha Marton
  - Christian Bartelt

links:
  Paper: https://arxiv.org/abs/2403.07733
  Code: https://github.com/patrick-knab/DSEG-LIME
  Demo: https://patrick-knab.github.io/DSEG-LIME/
---