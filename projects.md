---
layout: page
title: My Projects
subtitle: Here's Some Cool Stuff I've Done!
---
<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="button button-primary">Read More</a>
    </article>
  {% endfor %}
</div>

<!---
[markdown](http://en.wikipedia.org/wiki/Markdown)
-->
