---
layout: default
title: Blog
---

# Blog

Welcome to my blog! Here you'll find articles on various topics related to software development and my experiences in the industry.

## Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
