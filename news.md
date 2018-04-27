---
layout: default
title: News
permalink: /news/
---

<h1>News</h1>
<ul class="post-list">
    {% for post in site.posts %}
    <li>
        <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
