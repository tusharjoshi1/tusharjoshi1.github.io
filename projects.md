---
layout: page
title: My Projects
subtitle: Here's Some Cool Stuff I've Done!
---
<ul>
  {% for post in site.posts %}
    <div>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    <hr>
    </div>
  {% endfor %}
</ul>

<!---
[markdown](http://en.wikipedia.org/wiki/Markdown)
-->
