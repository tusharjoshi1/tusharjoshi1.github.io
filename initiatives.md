---
layout: page
title: Initiatives
subtitle: Here's Some Stuff I've Been A Part Of
---

<!-- {% assign posts = site.posts | where: "category", "initiative" %}-->
 <ul>
  {% for post in posts %}
    <div>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    <hr>
    </div>
  {% endfor %}
</ul>
