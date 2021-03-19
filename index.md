---
layout: default
title: Blog | Jose Javier Gonzalez Ortiz
header: JJGO &>  Blog
description: Quasirandom musings on programming, machine learning and computational puzzles
permalink: /
---

{% for post in site.posts %}

  <p><a href="{{ post.url }}">{{ post.title }}</a><br>
  {{ post.description }}<br>
  📅 {{ post.date | date_to_string }}</p>
{% endfor %}
