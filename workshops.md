---
layout: default
title: Workshops
permalink: /workshops/
---

<h1>Workshops</h1>
<ul class="post-list">
    {% for post in site.posts %}
        {% if post.type == "workshop_announcement" %}
        <li>
            <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </li>
        {% endif %}
    {% endfor %}
</ul>
