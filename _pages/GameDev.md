---
layout: page
title: Game Dev
permalink: /game-dev/
nav: true
nav_order: 5
---

Games I'm making, development logs, and things I've learned along the way.

{% assign posts = site.categories.game-development %}

{% for post in posts %}
## [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%B %-d, %Y" }}

{{ post.description }}

{% endfor %}
