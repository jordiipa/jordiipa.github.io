---
title: Index d'entrades al blog
subtitle: Tria i ramena
layout: page
show_sidebar: false
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

