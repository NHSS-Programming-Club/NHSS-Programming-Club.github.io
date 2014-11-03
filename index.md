---
layout: page
title: "About"
description: "Hello World!"
---
{% include JB/setup %}

##What is it?

The NHSS Programming club is a club at [Nashua High School South](http://schools.nashua.edu/Pages/default.aspx) ,
which was started in 2014

We are a group of students who are enthusiastic about programming and computer science.


Our goal is to develop cool software and programs, and to win several competitions that we participate in throughout the NorthEast region!

Check out this site to find interesting blog posts on software and various problem solving strategies


##Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>