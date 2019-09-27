---
layout: narrative
title: Essays
author: "ARTH046: Socially Engaged Art in the Americas Class"
---

--

## First Written Assignment

--

{% for post in site.arth %}  
  {% if post.title != "Essays" %}
  <a href="{{site.baseurl}}{{post.url}}">{{post.author}} // {{post.title}}</a>
  {% endif %}
{% endfor %}
