---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
_styles: >
  .container {
    max-width: calc(930px + (100vw - 930px) / 2);
  }
---

<!-- _pages/publications.md -->

<h2>Journal articles</h2>

<div class="publications">

{% bibliography --query @article %}

</div>

<h2>Working papers</h2>

<div class="publications">

{% bibliography --query @unpublished %}

</div>
