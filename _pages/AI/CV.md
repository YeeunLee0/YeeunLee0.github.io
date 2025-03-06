---
title: "📌 AI / CV"
layout: category
permalink: /AI/CV/
author_profile: true
sidebar_main: true
types: posts
taxonomy:
sidebar:
  nav: "sidebar-category"
  enabled: true
---

{% assign posts_with_AI = site.posts | where: "categories", "AI" %}
{% assign posts_with_AI_and_CV = posts_with_AI | where: "categories", "CV" %}

{% for post in posts_with_AI_and_CV %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}

