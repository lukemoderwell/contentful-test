---
layout: default
title: Authors
permalink: /authors/
---

<ul>
  {% for author in site.data.content_discovery.author %}
    <li>
      <img src="{{ author[1].avatar.url }}" />
      <h2>{{ author[1].name }}</h2>
      <p>{{ author[1].bio }}</p>
    </li>
  {% endfor %}
</ul>
