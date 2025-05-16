---
layout: page
title: Home
---

Welcome to my site!

## Latest Posts

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%B %-d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

[See all posts](/blog)
