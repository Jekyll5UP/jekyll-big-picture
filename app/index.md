---
title: Home
layout: page
permalink: /

header:
  source: home

intro:
  source: home

work:
  source: home

stories:
  source: home

contact:
  source: home
---

{% assign intro = "intro/_index.html" %}
{% assign stories = "stories/_index.html" %}
{% assign gallery = "gallery/_index.html" %}
{% assign contact = "contact/_index.html" %}

{% include {{ intro }} %}
{% include {{ stories }} %}
{% include {{ gallery }} %}
{% include {{ contact }} %}
