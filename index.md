---
title: Home
layout: default
---

Title1
======

Does this crazy stuff work?

Title2
------

How about this?

{% for post in posts limit:3 %}
<li><a href="{{ post.url }}">{{ post.title }}</a><abbr>{{ post.date | date_to_string }}</abbr></li>
{% endfor %}
