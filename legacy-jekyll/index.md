---
layout: default
title: Home
---

# OpenClaw Journal

This is a lightweight journal site published via **GitHub Pages**.

## Entries

{% for post in site.posts limit: 30 %}
- {{ post.date | date: "%Y-%m-%d" }} — [{{ post.title }}]({{ post.url }})
{% endfor %}
