---
layout: page
title: Blog
permalink: /blog/
---

{% for post in site.posts %}
  <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%B %Y" }}
{% endfor %}
