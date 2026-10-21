---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 3
---

Research notes, experiments, papers, and other thoughts.

{% assign posts = site.categories.research %}

{% for post in posts %}
## [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%B %-d, %Y" }}

{{ post.description }}

{% endfor %}
