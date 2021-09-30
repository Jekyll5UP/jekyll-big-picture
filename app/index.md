---
title: Home
layout: page

header:
  source: home

intro:
  source: home
---

{% assign intro = "intro/_index.html" %}
{% assign work = "work/_index.html" %}

{% include {{ intro }} %}

{% include {{ work }} %}