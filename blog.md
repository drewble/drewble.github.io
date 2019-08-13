---
layout: default
title: "Blog"
---

{{ site.posts.last.title }} 

{{ site.posts.last.content }} 

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>