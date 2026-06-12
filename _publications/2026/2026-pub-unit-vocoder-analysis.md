---
title:          "Multilingual Multi-Speaker Unit Vocoders: A Systematic Analysis of Discrete Speech Representations"
date:           2026-06-04
selected:       true
pub:            "Interspeech 2026"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Proceedings</span>'
pub_date:       "2026"
semantic_scholar_id: null  # use this to retrieve citation count
# abstract: >-
#   Discrete speech units obtained via k-means clustering of self supervised embeddings entangle phonetic, speaker, and language information, causing speaker mixing and cross-lingual interference in multilingual multi-speaker speech generation. Despite growing use in Audio LLMs and speech to speech systems, unit vocoders remain underexplored. We analyze a BigVGAN based unit vocoder, across four Indian languages. We study the interaction between cluster size and conditioning strategies using WER, speaker similarity, and unit level metrics. Results show that cluster size governs intelligibility by improving phonetic discriminability, while explicit speaker conditioning is indispensable for preventing identity collapse. Language supervision yields further gains mainly at lower cluster sizes where units remain ambiguous. Our analysis shows similar phonemes across languages collapse to the same cluster IDs at smaller inventories, with larger clusters progressively separating them.
cover:          /assets/images/covers/unit_vocoder_interspeech.png
authors:
  - Naman Kothari
  - Arjun Gangwar
  - Adarsh Arigala
  - S Umesh
links:
  #Code: https://github.com/ArigalaAdarsh/Reference-Guided-Targeted-Sound-Detection
  Paper: https://arxiv.org/abs/2606.06740
---
 