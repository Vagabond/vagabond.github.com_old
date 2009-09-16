---
title: Home
layout: default
---

Title2
------

How about this?

{% for post in site.posts limit:3 %}
<h3><a href="{{ post.url }}">{{ post.title }}</a> -- <abbr>{{ post.date | date_to_string }}</abbr></h3>
{{ post.content }}
<hr style="width: 40%;"/>
{% endfor %}
