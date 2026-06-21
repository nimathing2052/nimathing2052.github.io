---
layout: page
title: From LDA to BERTopic — Podcast Discourse Analysis
description: Transformer-based topic modelling of ASR-transcribed political podcasts
importance: 3
category: research
related_publications: false
---

A comparison of classical and transformer-based topic modelling applied to political podcasts. Working from Whisper-transcribed audio in the [SPoRC](https://huggingface.co/datasets/blitt/SPoRC) podcast corpus, I built a BERTopic model on transformer embeddings and benchmarked it against Latent Dirichlet Allocation.

The BERTopic pipeline achieved a topic-coherence score (C_v) above 0.731, a substantial improvement in interpretability over the LDA baseline. The resulting topics were used to explore political-communication and audience-engagement patterns across the podcast ecosystem.

**Stack:** Python, BERTopic, LDA, Whisper, sentence embeddings.  
**Code:** [github.com/nimathing2052/SPoRC_TopicModeling](https://github.com/nimathing2052/SPoRC_TopicModeling).  
**Coursework:** Natural Language Processing
