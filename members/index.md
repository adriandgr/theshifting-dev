---
layout: archive
title: "Members"
date: 2014-05-30T11:40:45-04:00
modified:
excerpt: "Learn more about the individuals that make up The Shifting"
tags: []
image:
  feature:
  teaser:
---

{% for cat in site.categories %}
    <li>{{ cat[0] }}</li>
{% endfor %}
