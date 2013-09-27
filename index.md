---
layout: page
title: Francisco Ruiz A
tagline: /dev/hell
---
{% include JB/setup %}

> *husband, kick-ass dad, technologyst, web developer and taco enthusiast*  


## Posts ##
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>


