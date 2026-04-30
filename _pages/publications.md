---
layout: page
permalink: /publications/
title: publications
description: My peer-reviewed publications and preprints.
nav: true
nav_order: 2
---


<!-- _pages/publications.md -->
<div class="publications">

<h1 class="publication-section-heading">Peer-reviewed papers</h1>

{% bibliography --query @*[peer_reviewed=true]* %}

<h1 class="publication-section-heading">Preprints</h1>

{% bibliography --query @*[preprint=true]* %}

</div>
