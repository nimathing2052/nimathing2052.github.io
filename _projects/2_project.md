---
layout: page
title: Multimodal TikTok Virality Prediction
description: Multimodal machine-learning pipeline for political virality in Nepal's 2022 elections (MSc thesis)
importance: 1
category: research
related_publications: false
---

A multimodal machine-learning pipeline built for my master's thesis at the Hertie School, studying political virality and engagement on TikTok during Nepal's 2022 local elections.

The pipeline collected 28,165 political TikTok videos and assembled a multimodal sample of 2,964 videos, fusing audio features (OpenAI Whisper), visual features (CLIP), and platform metadata. A gradient-boosted model (XGBoost) reached an AUC of 0.800 under 5×5 cross-validation. The design separates description, prediction, and association so that predictive performance is not mistaken for causal explanation. An OLS component relates engagement to communicative style and political theme, using a hand-built codebook and a zero-shot classifier for Nepalese political-stance detection.

The work is a methodological contribution to studying political communication in a low-resource, multilingual electoral context.

**Stack:** Python, scikit-learn, XGBoost, CLIP, Whisper.  
**Thesis:** [Nima_Thing_MSc_Thesis_Draft_revised_v2.pdf](https://github.com/nimathing2052/Thesis-Revision/blob/main/Nima_Thing_MSc_Thesis_Draft_revised_v2.pdf) (submitted and completed, 2025; revised after committee feedback).  
**Code:** [github.com/nimathing2052/TikTok_MultiModal_Virality_Prediction](https://github.com/nimathing2052/TikTok_MultiModal_Virality_Prediction). 
