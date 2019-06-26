---
title:  "Schaver.com"
author: Mark
---

# 'In the world of diplomacy, some things are better left unsaid.'

~ Lincoln Chafee

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>