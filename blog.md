---
layout: default
title: Blog
permalink: /blog/
---

<h2 style="margin: 80px 0px 10px;"></h2>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
