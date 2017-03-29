---
layout: archive
title: FOSS4G Boston Blog
date: {{ date }}
modified:
excerpt:
image:
  feature:
  teaser:
  thumb:
---

test blog page

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
