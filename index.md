---
title: Jobert Leong
author : Jobert
description : Test description
---
# Jobert Leong | Trombonist
<br>
<img src ="./assets/images/PFP1.JPG" alt="Jobert with trombone near SkyTrain."/>

Hi, I'm Jobert. If you need someone to play the trombone, look no further.

I do plenty of other things as well, so feel free to check them out while you're here.

## Blog (Coming Soon!)

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
