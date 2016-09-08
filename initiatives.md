---
layout: page
title: Initiatives
subtitle: Here's Some Stuff I've Been A Part of
---

Currently Being Updated.

<div class="postsi">
  {% for post in site.postsi %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="button button-primary">Read More</a>
    </article>
  {% endfor %}
</div>

