---
layout: page
title: Blog
---
Einiges, das in der Wilden Linde passiert ist:

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%Y/%m/%d"}} <a href="{{ post.url }}">{{ post.title }}</a> 
    </li>
  {% endfor %}
</ul>
