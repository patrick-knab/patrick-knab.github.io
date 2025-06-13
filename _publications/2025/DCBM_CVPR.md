---
title:          "DCBM: Data-Efficient Visual Concept Bottleneck Models"
date:           2025-10-06 00:01:00 +0800
selected:       true
pub:            "Conference on Computer Vision and Pattern Recognition (CVPR) @ XAI4CV Workshop"
pub_date:       "2025"
abstract: >-
  Concept Bottleneck Models (CBMs) enhance the interpretability of neural networks by basing predictions on human-understandable concepts. However, current CBMs typically rely on concept sets extracted from large language models or extensive image corpora, limiting their effectiveness in data-sparse scenarios. We propose Dataefficient CBMs (DCBMs), which reduce the need for large sample sizes during concept generation while preserving interpretability. DCBMs define concepts as image regions detected by segmentation or detection foundation models, allowing each image to generate multiple concepts across different granularities. This removes reliance on textual descriptions and large-scale pre-training, making DCBMs applicable for fine-grained classification and out-of-distribution tasks. Attribution analysis using Grad-CAM demonstrates that DCBMs deliver visual concepts that can be localized in test images. By leveraging dataset-specific concepts instead of predefined ones, DCBMs enhance adaptability to new domains.
  
authors:
- Katharina Prasse*
- Patrick Knab*
- Sascha Marton
- Christian Bartelt
- Margret Keuper

links:
  Paper: https://drive.google.com/file/d/15L1jEj0P0VANrtaRN1TaGL0HCUfCEh6Z/view
  Code: https://github.com/KathPra/DCBM
  Demo: https://kathpra.github.io/DCBM/
---