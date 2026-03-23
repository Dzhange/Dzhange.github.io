---
layout: default
title: "Projects"
permalink: /projects/
---

<div class="container">
  <div class="archive-page">
    <h1 class="page-title">Projects</h1>

    {% include base_path %}

    {% for post in site.researches reversed %}
      {% include archive-single.html %}
    {% endfor %}
  </div>
</div>
