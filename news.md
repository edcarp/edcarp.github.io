---
layout: default
title: News
permalink: /news/
---

<h1>News</h1>
<ul class="post-list">
    {% for post in site.posts %}
    <li>
        <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span><br/>
        <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
