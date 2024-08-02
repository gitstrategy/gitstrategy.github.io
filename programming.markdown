---
layout: page
title: Programming
permalink: /programming/
---

<ul>
{% for post in site.posts %}
    {% if post.categories contains "programming" %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
