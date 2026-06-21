---
layout: page
permalink: /publications/
title: research outputs
description: Manuscripts, working papers, and presentations. I do not yet have peer-reviewed publications; the items below are research outputs — a submitted manuscript, working papers, a thesis, policy writing, and talks and posters.
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">Manuscripts &amp; Writing</h2>

{% bibliography --query @*[category=writing] %}

<h2 class="bibliography">Presentations &amp; Posters</h2>

{% bibliography --query @*[category=presentation] %}

</div>
