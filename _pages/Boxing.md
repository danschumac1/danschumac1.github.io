---
layout: page
title: Boxing
permalink: /boxing/
nav: true
nav_order: 6
---

Training notes, experiences, and reflections from the gym.

{% assign posts = site.categories.boxing %}

{% for post in posts %}
## [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%B %-d, %Y" }}

{{ post.description }}

{% endfor %}