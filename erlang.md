---
layout: default
title: code
---
<ul id="archive">
{% for post in site.categories.erlang %}
<li><a href="{{ post.url }}">{{ post.title }}</a><abbr>{{ post.date | date_to_string }}</abbr></li>
{% endfor %}
</ul>
