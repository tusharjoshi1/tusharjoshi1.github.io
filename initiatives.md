---
layout: page
title: Initiatives
subtitle: Here's Some Stuff I've Been A Part of
---
<html>

<head>
<subtitle>HTML Reference</subtitle>
</head>

<body>
The content of the document......
</body>

</html>


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
