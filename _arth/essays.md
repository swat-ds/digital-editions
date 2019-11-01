---
layout: narrative
title: Essays
author: "ARTH046: Socially Engaged Art in the Americas Class"
---
<br/>
## *Third Written Assignment*
--
{% for post in site.arth %}  
  {% if post.week == "three" %}
  <a href="{{site.baseurl}}{{post.url}}">{{post.author}} // {{post.title}}</a>
  {% endif %}
{% endfor %}

<hr>

## *Second Written Assignment*
--
{% for post in site.arth %}  
  {% if post.week == "two" %}
  <a href="{{site.baseurl}}{{post.url}}">{{post.author}} // {{post.title}}</a>
  {% endif %}
{% endfor %}

<hr>

## *First Written Assignment*
--
{% for post in site.arth %}  
  {% if post.week == "one" %}
  <a href="{{site.baseurl}}{{post.url}}">{{post.author}} // {{post.title}}</a>
  {% endif %}
{% endfor %}
