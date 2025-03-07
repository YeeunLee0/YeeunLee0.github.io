---
title: "Multimodal"
layout: archive
permalink: categories/Multimodal
author_profile: true
types: posts
---

{% assign posts = site.categories['Multimodal']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}