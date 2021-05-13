---
layout: page
title: Portal
permalink: /portal
---

<div>
  <div class="post-heading">
    <h1 class="post-title"> ◌ Portal ◌ </h1>
    <p>Lessons, sparks, teachings. Some from warm hearts and others from long-held traditions. Some others take the form of quotidian magic, a different lens. Letting them move through me like water. Passing them on, letting them drift your way.</p>
    <hr>
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


