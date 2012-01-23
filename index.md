---
layout: page
title: Home
---


This is the latest incarnation of George K. Thiruvathukal's home page, powered by [Jekyll](http://jekyllrb.com) and GitHub. This replaces my former page at Google Sites, which should become unavailable shortly. Please make a note of it.

In the spirit of userdirs and to celebrate the awesomeness of Unix, I have
decided to name my new site **~gkt**.

<ul class="posts">
  {% for post in site.posts limit: 5 %}
    <li>
            <span>{{ post.date | date_to_string }}&nbsp;</span> 
            &raquo; 
            <a href="{{ post.url }}">{{ post.title }}</a> <br/>
            <em>{{ post.excerpt }} </em>
            <br/>
    </li>
  {% endfor %}
</ul>

To view older posts, see the [archive](/archive.html).
