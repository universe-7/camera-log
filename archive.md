---
layout: page
title: notes by date
---

{% for post in site.posts %}
  ❍ {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ](/camera-log/{{ post.url }})
{% endfor %}