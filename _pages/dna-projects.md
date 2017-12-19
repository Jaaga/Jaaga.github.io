---
layout: dna
title: DNA Projects
description: 
feature_image: /assets/images/dna-projects.jpg
tags:
published: true
permalink: /dna/projects/
---

<div class="kg-card-markdown"><p>Our projects typically connect communities and bring people together to work on urban issues. We bring government, private organisations and individuals together towards positive and productive change. </p>
</div>
<br/>

<div class="columns is-multiline">
{% for page in site.pages %}
{% if page.tags == "dna-project" %}
<div class="column is-6">
  {% include project_card.html %}
</div>
{% endif %}
{% endfor %}
</div>
