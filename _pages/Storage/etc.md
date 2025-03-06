---
title: "🧰 Storage / Etc"
layout: category
permalink: /Storage/Etc/
author_profile: true
sidebar_main: true
types: posts
taxonomy:
sidebar:
  nav: "sidebar-category"
  enabled: true
---

{% assign posts_with_Storage = site.posts | where: "categories", "Storage" %}
{% assign posts_with_Storage_and_etc = posts_with_Storage | where: "categories", "etc" %}

{% for post in posts_with_Storage_and_etc %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}

