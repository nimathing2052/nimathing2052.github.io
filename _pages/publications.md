---
layout: page
permalink: /publications/
title: research outputs
description: Working papers, thesis, policy writing, talks, and posters.
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
