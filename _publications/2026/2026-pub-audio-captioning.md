---
title:          "Enhancing Audio Captioning with Auxiliary AudioSet Semantics"
date:           2026-06-04
selected:       true
pub:            "arXiv"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
#pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Proceedings</span>'
pub_date:       "2026"
semantic_scholar_id: null  # use this to retrieve citation count
# abstract: >-
#   Automatic Audio Captioning (AAC) seeks to generate natural language descriptions of complex acoustic scenes, bridging auditory perception and language understanding. However, word-selection indeterminacy and increasing reliance on large-scale sequence-to-sequence or LLM-based models limit practical deployment. We propose a resource-efficient AAC framework that explicitly grounds caption generation in auxiliary AudioSet semantics. Frame-level acoustic representations extracted using a ConvNeXt encoder are augmented with top-  predicted AudioSet keywords, providing structured contextual cues for decoding. A compact six-layer BART-style decoder conditions on this joint acoustic-semantic representation, enabling caption generation without LLM-scale decoding. The proposed design balances semantic grounding and computational efficiency within a compact architecture. Evaluations on Clotho V2 and AudioCaps confirm competitive caption quality under practical deployment constraint.
cover:          /assets/images/covers/AudioCaptioning.png
authors:
  - Shubham Gupta*
  - Adarsh Arigala*
  - Sri Rama Murty Kodukula
links:
  #Code: https://github.com/ArigalaAdarsh/Reference-Guided-Targeted-Sound-Detection
  Paper: https://arxiv.org/abs/2606.05717
---
