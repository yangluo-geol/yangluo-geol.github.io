---
title: "Teaching"
permalink: /teaching/
layout: single
---

{% for post in site.teaching %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.date | date: "%Y" }} at {{ post.venue }}</p>
{% endfor %}
