---
layout: default
title: News and Events
permalink: /events/
---

<h3>Upcoming and past events</h3>
<ul class="post-list">
    {% for post in site.posts %}
    {% if post.type == 'event_announcement' %}
    <li>
        <a class="post-link" href="{{ post.website }}">{{ post.title }}, {{ post.location }}, {{ post.when }}</a>
    </li>
    {% endif %}
    {% endfor %}
</ul>
