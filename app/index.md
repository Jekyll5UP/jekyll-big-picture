---
title: Home
layout: page

header:
  source: home

intro:
  source: home

work:
 source: home
---

{% assign intro = "intro/_index.html" %}
{% assign story = "story/_index.html" %}
{% assign gallery = "gallery/_index.html" %}
{% assign contact = "contact/_index.html" %}

{% include {{ intro }} %}
{% include {{ story }} %}
{% include {{ gallery }} %}
{% include {{ contact }} %}