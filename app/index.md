---
title: Home
layout: page

header:
  source: home

intro:
  source: home
---

{% assign intro = "intro/_index.html" %}
{% assign one = "one/_index.html" %}
{% assign two = "two/_index.html" %}
{% assign work = "work/_index.html" %}

{% include {{ intro }} %}
{% include {{ one }} %}
{% include {{ two }} %}
{% include {{ work }} %}