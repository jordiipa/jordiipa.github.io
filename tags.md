---
title: Etiquetes dels articles al blog
subtitle: Tria i ramena
layout: page
show_sidebar: false
hero_height: is-small
---

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}


