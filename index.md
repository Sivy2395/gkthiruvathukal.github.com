---
layout: page
title: George K. Thiruvathukal
---

My actual web page still lives at [www.thiruvathukal.com](http://www.thiruvathukal.com). I am exploring alternatives to hosted CMS/Blogging solutions that
allow me to author pages in plaintext, backed by a DVCS.

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

