---
layout: page
title: Elfbot — Agentic AI for Human-in-the-Loop Fact-Checking
description: LLM-agent system for digital-trace analysis and disinformation triage
importance: 1
category: infrastructure
related_publications: false
---

Elfbot is a human-in-the-loop agentic AI system for digital-trace analysis and disinformation triage, developed at [logiq.media](https://www.logiq.media) where I am the lead developer. This was the early stage version, which had broad functionalities, but right now I am developing v2 (https://github.com/nimathing2052/elfbot-comment-moderation) [Sorry it's private atm]

But this first version, uses LLM agents query multiple evidence sources — Wikidata, Tavily, and DuckDuckGo — to assemble multi-source evidence and produce citation-linked, confidence-calibrated outputs at the level of individual claims. Coordinated-behaviour signals such as burst dynamics and account clusters (on Bluesky and X/CSV samples) are surfaced for human review rather than auto-flagged. 

**Stack:** Python, LLM agents, MCP, retrieval (Tavily/Wikidata), reproducible pipelines.  
**Code:** [github.com/nimathing2052/elfbot_prototype](https://github.com/nimathing2052/elfbot_prototype). 
[demo](https://elfbot-prototype.onrender.com/). 
[Pitch Video(presented by my Colleague, Tom)](https://www.youtube.com/watch?v=VetENEzbFA8). 
