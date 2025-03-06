---
title: "📌 AI / Multimodal"
layout: category
permalink: /AI/Multimodal/
author_profile: true
sidebar_main: true
types: posts
taxonomy:
sidebar:
  nav: "sidebar-category"
  enabled: true
---

{% assign posts_with_AI = site.posts | where: "categories", "AI" %}
{% assign posts_with_AI_and_Multimodal = posts_with_AI | where: "categories", "Multimodal" %}

{% for post in posts_with_AI_and_Multimodal %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}

