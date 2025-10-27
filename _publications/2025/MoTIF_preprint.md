---
title:          "Concepts in Motion: Temporal Bottlenecks for Interpretable Video Classification"
date:           2025-10-01 00:03:00 +0800
selected:       true
pub:            "Preprint"
pub_date:       "2025"
abstract: >-
  Conceptual models such as Concept Bottleneck Models (CBMs) have driven substantial progress in improving interpretability for image classification by leveraging human-interpretable concepts. However, extending these models from static images to sequences of images, such as video data, introduces a significant challenge due to the temporal dependencies inherent in videos, which are essential for capturing actions and events. In this work, we introduce MoTIF (Moving Temporal Interpretable Framework), an architectural design inspired by a transformer that adapts the concept bottleneck framework for video classification and handles sequences of arbitrary length. Within the video domain, concepts refer to semantic entities such as objects, attributes, or higher-level components (e.g., 'bow', 'mount', 'shoot') that reoccur across time - forming motifs collectively describing and explaining actions. Our design explicitly enables three complementary perspectives: global concept importance across the entire video, local concept relevance within specific windows, and temporal dependencies of a concept over time. Our results demonstrate that the concept-based modeling paradigm can be effectively transferred to video data, enabling a better understanding of concept contributions in temporal contexts while maintaining competitive performance. Code available at github.com/patrick-knab/MoTIF.

cover:          /assets/images/covers/VBM.png

authors:
  - Patrick Knab
  - Sascha Marton
  - Philipp J Schubert
  - Drago Guggiana
  - Christian Bartelt

links:
  Paper: https://arxiv.org/abs/2509.20899
  Code: https://patrick-knab.github.io/MoTIF/
  Demo: https://patrick-knab.github.io/DSEG-LIME/
---