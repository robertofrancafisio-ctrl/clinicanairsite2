---
layout: home
title: Blog
permalink: /blog/
---

<h1>Blog da Clínica Nair Franca</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%d/%m/%Y" }}
    </li>
  {% endfor %}
</ul>
