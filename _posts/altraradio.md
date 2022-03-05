---
title: Quadern de treball
subtitle: Alguns guions per a l'Altra Ràdio
layout: page
show_sidebar: false
hero_height: is-medium
---

# L'Altra Ràdio 

Recull d'alguns guions dels micro espais que en Cinto Niqui, director del programa, amablement m'ofereix. [L'Altra Ràdio](https://www.altraradio.cat/), a Ràdio 4.

Els [podcasts](https://www.rtve.es/play/audios/laltra-radio/).

Els mini guions:

{% for tag in site.tags %}
  {% if tag[0] == "Altra Ràdio" %}
  <ul>
    {% for post in tag[1] %}
       <li>{{post.date | date: "%Y %b %-d" }} <a href="{{ post.url }}"> -  {{ post.title }}</a></li>
    {% endfor %}
  </ul>
  {% endif %} 
{% endfor %}
