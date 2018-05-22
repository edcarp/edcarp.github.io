---
layout: default
title: Workshops
permalink: /workshops/
---

# Workshops

- [SWC workshop, 03-04 July, Room 3.214, University Place, Wilmslow Road, University of Manchester](_posts/2018-05-08-swc-workshop.md)
- [DC workshop, 23-24 May, Humanities Bridgeford Street, University of Manchester](_posts/2018-04-27-dc-workshop.md)
- [SWC workshop, 15-16 May, Kilburn Building, University of Manchester](_posts/2018-04-27-swc-workshop.md)


<h1>News</h1>
<ul class="post-list">
    {% for post in site.posts %}
    <li>
        <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
