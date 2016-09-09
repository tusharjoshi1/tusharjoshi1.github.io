---
layout: page
title: Initiatives
subtitle: Here's Some Stuff I've Been A Part of
---
<html> 
  <head>
    <title>Legacy Canada</title>
  </head>
  <body>
  Legacy is Canada’s biggest student led entrepreneurship conference. From April 2015 to 2016 I was fortunate to be a part of the Growth and Academic team. Through this role I was able build relationships with a large number of students, faculty and entrepreneurial communities.
Working closely with the Executive Director and the Director of marketing, we were able to bring out over 550 delegates and have over 16 institutions represented.  
Find out more about Legacy <a href="httpshttp://www.legacycan.ca/">Here</a>! 
</body>







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
