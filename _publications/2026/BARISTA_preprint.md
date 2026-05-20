---
title:          "BARISTA: A Multi-Task Egocentric Benchmark for Compositional Visual Understanding"
date:           2026-05-12 00:01:00 +0800
selected:       true
pub:            "Preprint"
pub_date:       "2026"

abstract: >-
  Scene understanding is central to general physical intelligence, and video is a primary modality for capturing both state and temporal dynamics of a scene. Yet understanding physical processes remains difficult, as models must combine object localization, hand-object interactions, relational parsing, temporal reasoning, and step-level procedural inference. Existing benchmarks usually evaluate these capabilities separately, limiting diagnosis of why models fail on procedural tasks. We introduce BARISTA, a densely annotated egocentric dataset and benchmark of 185 real-world coffee-preparation videos covering fully automatic, portafilter-based, and capsule-based workflows. BARISTA provides verified per-frame scene graphs linking persistent object identities to masks, tracks, boxes, attributes, typed relations, hand-object interactions, activities, and process steps. From these graphs, we derive zero-shot language-based tasks spanning phrase grounding, hand-object interaction recognition, referring, activity recognition, relation extraction, and temporal visual question answering. Experiments reveal strong variation across task families and no consistently dominant model family, positioning BARISTA as a challenging diagnostic benchmark for procedural video understanding.

cover:          /assets/images/covers/barista.png

authors:
  - Patrick Knab*
  - Orgest Xhelili*
  - Inis Buzi
  - Drago Andres Guggiana Nilo
  - Mohd Saquib Khan
  - Lorenz Kolb
  - Manuel Scherzer
  - Kerem Yildirir
  - Christian Bartelt
  - Philipp Johannes Schubert

links:
  Paper: https://arxiv.org/abs/2605.12074
  Dataset: https://huggingface.co/datasets/ramblr/BARISTA
  Ramblr: https://ramblr.ai
---
