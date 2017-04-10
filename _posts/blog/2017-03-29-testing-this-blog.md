---
layout: article
title: testing this blog
modified:
categories: test news updates stuff
excerpt:
tags: []
image:
  feature:
  teaser:
  thumb:
author:
  name: Guido Stein
---

This is a post

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
