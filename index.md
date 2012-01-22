---
layout: page
title: George K. Thiruvathukal
---

Welcome to my new web site, powered by [Jekyll](http://jekyllrb.com).

I am still migrating content from my previous [Google Site](http://home.thiruvathukal.com) and will continue to keep it around in the interim, especially for 
those who have links to it.

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

