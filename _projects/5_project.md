---
layout: page
title: Elfbot — Human-in-the-Loop AI for Comment Moderation & Disinformation Triage
description: From LLM-agent disinformation triage (v1) to AI-based Facebook comment moderation (v2)
importance: 1
category: infrastructure
related_publications: false
---

Elfbot is a human-in-the-loop AI system developed at [logiq.media](https://www.logiq.media), where I am the lead developer. The current version (v2) focuses on AI-based Facebook comment moderation: a backend for ingestion, polling, and webhooks, and a core pipeline combining classifier rules with fine-tuned LLMs to detect trolls and toxic comments — with human review kept in the loop rather than auto-flagging ([repo](https://github.com/nimathing2052/elfbot-comment-moderation) private at the moment).

The first version (v1, linked below) was broader in scope, built for digital-trace analysis and disinformation triage.

This first version uses LLM agents to query multiple evidence sources — Wikidata, Tavily, and DuckDuckGo — to assemble multi-source evidence and produce citation-linked, confidence-calibrated outputs at the level of individual claims. Coordinated-behaviour signals such as burst dynamics and account clusters (on Bluesky and X/CSV samples) are surfaced for human review rather than auto-flagged.

**Stack:** Python, LLM agents, MCP, retrieval (Tavily/Wikidata), reproducible pipelines.  
**Code:** [github.com/nimathing2052/elfbot_prototype](https://github.com/nimathing2052/elfbot_prototype).
[demo](https://elfbot-prototype.onrender.com/).
[Pitch Video(presented by my Colleague, Tom)](https://www.youtube.com/watch?v=VetENEzbFA8).
