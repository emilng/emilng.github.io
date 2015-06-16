---
layout: default
title: Blog
permalink: /blog/
---
<h2>Blog</h2>
<ul class="posts clearfix">
  {% for post in site.posts %}
    <li><span class="posts-title"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></span><span class="posts-date">{{ post.date | date_to_string }}</span></li>
  {% endfor %}
</ul>