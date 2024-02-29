---
title: Documentation
layout: page
---

<div class="documentation">{{ page.title }}</div>
<ul>
  {% for post in site.posts %}
    <li>
      <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
      {{ post.excerpt }}
    </li>
  {% endfor %}

</ul>
