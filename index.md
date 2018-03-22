---
title: Ottan's GitHub Pages
project_title:  Ottan's GitHub Pages
---

## Articles

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>