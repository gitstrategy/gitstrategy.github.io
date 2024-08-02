---
layout: page
title: Java 
permalink: /java/
---

<ul>
{% for post in site.posts %}
    {% if post.categories contains "java" %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
