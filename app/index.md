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
{% assign one = "one/_index.html" %}
{% assign work = "work/_index.html" %}
{% assign contact = "contact/_index.html" %}

{% include {{ intro }} %}
{% include {{ one }} %}
{% include {{ work }} %}
{% include {{ contact }} %}