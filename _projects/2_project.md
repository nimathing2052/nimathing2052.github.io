---
layout: page
title: "Beyond the Ballot: TikTok Virality in Nepal's 2022 Local Elections"
description: MSc thesis — multimodal analysis of political attention on TikTok
importance: 1
category: research
related_publications: false
---

My master's thesis at the Hertie School, supervised by [Prof. Simon Munzert](https://simonmunzert.github.io/), asks how political content gained attention on TikTok during Nepal's 2022 local elections.

I collected 28,165 election-related videos through TikTok's Research API and analyzed a view-stratified sample of 2,964. The multimodal pipeline combines Whisper transcripts, GPT-4o image captions and translations, multilingual text embeddings, and platform metadata. I hand-coded communication styles with a codebook developed for the study.

**What I found.** Attention was moderately predictable after the fact (cross-validated AUC 0.80), but most of the signal came from how large the posting accounts already were. Videos about independent candidates drew more attention than general election content, and this association held across robustness checks. Style results are exploratory, because the style labels had only moderate agreement between coders. None of these results are causal.

I revised the thesis in October 2026. The next step is a re-analysis with sampling weights, separate reach and engagement outcomes, and an independent second coder.

**Presented at:** TCSS 2026 (Koç University, talk); _Youth in a Digital Society_, University of Potsdam (poster, October 2026); SICSS-Saarbrücken and MPIB Berlin (posters, 2025).

**Methods:** Python, XGBoost, OLS regression, Whisper, GPT-4o.  
**Thesis:** [PDF](https://github.com/nimathing2052/Thesis-Revision/blob/main/Nima_Thing_MSc_Thesis_Draft_revised_v2.pdf) · **Poster:** [Potsdam 2026](https://drive.google.com/file/d/1p2l4XnWOSzSkKayU1wcdyvEOECyb35LP/view?usp=sharing) · **Code:** [GitHub](https://github.com/nimathing2052/TikTok_MultiModal_Virality_Prediction)
