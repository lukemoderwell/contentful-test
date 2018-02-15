---
layout: default
---

<ul>
  {% for article in site.data.content_discovery.article %}
    <li>
      <a href="{{site.url}}{{ article[1].slug }}"><h2>{{ article[1].title }}</h2></a>
    </li>
  {% endfor %}
</ul>
