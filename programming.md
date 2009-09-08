---
layout: default
title: programming
---
<ul id="archive">
{% for post in site.categories.programming %}
<li><a href="{{ post.url }}">{{ post.title }}</a><abbr>{{ post.date | date_to_string }}</abbr></li>
{% endfor %}
</ul>
