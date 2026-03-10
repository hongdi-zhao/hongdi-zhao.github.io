---
page_id: papers
layout: page
permalink: /papers/
title: papers
description: papers by year
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">

  <h2>Working Papers</h2>
  {% bibliography -f working_papers %}

  <h2>Work in Progress</h2>
  {% bibliography -f work_in_progress %}

  <h2>Publications</h2>
  {% bibliography -f publications --group_by year --group_order descending %}

</div>
