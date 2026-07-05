---
title: Jobert Leong
author : Jobert
description : Test description
---
# Jobert Leong | Trombonist

<img src ="./assets/images/PFP1.JPG" alt="Jobert with trombone near SkyTrain."/>

Welcome to the official website of Jobert Leong.

## Blog (Test)

### Latest Post
<ul>
  {% for post in site.posts limit:1 %}
  <li>
    <a href="{{ post.url }}">{{ post.date | date: "%Y %B %e" }} - {{ post.title }}</a>
  </li>
  {% endfor %}
</ul>

### Recent Posts
<ul>
  {% for post in site.posts offset:1 limit:2 %}
  <li>
    <a href="{{ post.url }}">{{ post.date | date: "%Y %B %e" }} - {{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
