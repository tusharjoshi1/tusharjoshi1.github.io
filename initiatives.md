---
layout: page
title: Initiatives
subtitle: Here's Some Stuff I've Been A Part of
---

Currently Being Updated.
<ul>
  {% for post in site.postsi %}
    <div>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    <hr>
    </div>
  {% endfor %}
</ul>
