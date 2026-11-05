---
title:          "Intervenable Concept Dynamics for Video Activity Forecasting"
paper_id:       trace-cbm
date:           2026-11-05 10:00:00 +0100
selected:       true
pub:            "NeurIPS 2026 Workshop on Foundation Models for Temporal Systems: From Forecasting to World Modeling (FMTS)"
pub_date:       "2026"
abstract: >-
  Concept bottleneck models route predictions through human-understandable concepts, making their intermediate states inspectable and editable. Extending this model family to forecasting requires modeling how concept activations evolve over time as objects, actions, and their interactions change, yet existing CBMs ground concepts only in observed inputs and do not forecast their future evolution. We study this problem using videos of ongoing activities and forecast future activities through a named-concept state. We propose TRACE-CBM (Temporal Relational Activity Concept Evolution), which first refines observed concept activations with sparse spatio-temporal graphs. It then recursively predicts future concept states, conditioning each transition on the prior activity distribution, and decodes both observed and predicted states with a shared activity classifier. At inference time, the model supports editing concept values, activity activations, and learned edges without parameter updates, exposing the relational spatio-temporal dependencies used for forecasting. Across multiple datasets, TRACE improves observed-activity Top-1 accuracy over concept-based methods by 1.2-8.5 percentage points and attains H3 forecast Top-1 accuracy within 1.9-2.2 points of matched black-box forecasters. Intervention experiments show concept-node edits correct 25.6-34.4% of initially incorrect H3 forecasts without flipping initially correct ones, and concept steering achieves the requested target activity in up to 90.0% of cases.
authors:
  - Patrick Knab
  - David Steinmann
  - Giovanni De Felice
  - Felix Divo
  - Udo Schlegel
  - Wolfgang Stammer
  - Sascha Marton
  - Christian Bartelt
links:
  Paper: https://arxiv.org/abs/2611.00020
---
