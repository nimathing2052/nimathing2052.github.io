---
layout: page
title: Bias Detection & Mitigation in Transformer Models
description: Fine-tuning DistilBERT for hate-speech detection with fairness diagnostics
importance: 2
category: research
related_publications: false
---

A study of representational fairness in transformer-based text classifiers. As my major contribution to this group project, I fine-tuned DistilBERT on the Jigsaw dataset to detect hate speech, then applied the FHI365 fairness framework to measure and mitigate bias across demographic groups.

The resulting model achieved an F1-score of 0.68 while surfacing a 22% demographic-parity gap, illustrating the tension between predictive performance and group fairness in content-moderation models.

As lead author, I presented these findings on representational fairness at [*SSaLM: Social Science & Language Models*](https://lppohl.github.io/wi-workshop.github.io/content/0-program.html) at the Weizenbaum Institute in April 2025.


**Stack:** Python, PyTorch, DistilBERT, fairness diagnostics.  
**Code:** [Colab notebook](https://colab.research.google.com/drive/15V6bZnLlEvDTRuMDE3SxCeiUmMbFoiR3). 
**Coursework:** Deep Learning
