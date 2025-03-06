---
title: "📌 Data Engineering / SQL"
layout: category
permalink: /Data Engineering/SQL/
author_profile: true
sidebar_main: true
types: posts
taxonomy:
sidebar:
  nav: "sidebar-category"
  enabled: true
---

{% assign posts_with_Data Engineering = site.posts | where: "categories", "Data Engineering" %}
{% assign posts_with_Data Engineering_and_SQL = posts_with_Data Engineering | where: "categories", "SQL" %}

{% for post in posts_with_Data Engineering_and_SQL %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}

