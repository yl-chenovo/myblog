---
layout: default
title: 神的摄影
---

# 基告摄 🐱

我会在这里放一点猫毛：🐱

{% for post in site.categories.photo %}
  - {{ post.date | date: "%Y-%m-%d" }}  
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
