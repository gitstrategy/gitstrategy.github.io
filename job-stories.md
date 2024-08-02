---
layout: page
title: Job Stories
permalink: /job-stories/
---

<ul>
{% for post in site.posts %}
    {% if post.categories contains "job-stories" %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
