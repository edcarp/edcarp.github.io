---
layout: default
title: Workshops
permalink: /workshops/
---

<h3>Upcoming and past workshops</h3>
<ul class="post-list">
    {% for post in site.posts %}
    {% if post.type == 'workshop_announcement' %}
    <li>
        <a class="post-link" href="{{ post.website }}">{{ post.title }}, {{ post.location }}, {{ post.when }}</a>
    </li>
    {% endif %}
    {% endfor %}
</ul>
