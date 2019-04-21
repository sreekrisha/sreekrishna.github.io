---
layout: default
title: Events
permalink: /Events/
---
<h2>Latest Events </h2>
{% for post in site.posts %}
  <a href="{{ post.url }}">{{ post.title }}</a>
  <p>{{ post.excerpt }}</p>
{% endfor %}
