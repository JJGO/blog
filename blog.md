---
layout: default
title: Blog | Simple Jekyll
header: Blog
description: Where the magic happens - this is the blog!
permalink: /blog/
---

{% for post in site.posts %}
  <p><a href="{{ post.url }}">{{ post.title }}</a><br>
  {{ post.description }}<br>
  📅 {{ post.date | date_to_string }}</p>
{% endfor %}
