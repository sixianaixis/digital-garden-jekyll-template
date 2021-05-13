---
layout: default
title: Writing
permalink: /writing
---

<div>
  <div class="post-heading">
    <h1 class="post-title">◌ Writing ◌</h1>
  </div>
  {% for post in site.posts limit: post_limit %}
  <div class="list-entry">
    <div><a class="blogpost-title-index" href="{{ post.url }}">{{ post.title }}</a> 
    <span class="date">({{ post.date | date: "%Y.%m.%d" }})</span></div>
  </div>
    <div>{{ post.excerpt }}</div>
    <br>
  
  {% endfor %}
  <br>

</div>