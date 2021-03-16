---
layout: default
title: Blog | Jose Javier Gonzalez Ortiz
header: Blog
description: Pseudorandom musings on programming, machine learning and puzzles
permalink: /blog/
---

{% for post in site.posts %}

  <p><a href="{{ post.url }}">{{ post.title }}</a><br>
  {{ post.description }}<br>
  📅 {{ post.date | date_to_string }}</p>
{% endfor %}
