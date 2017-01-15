---
layout: archive
title: Archive
description: 历史文章
keywords: 历史文章
comments: false
menu: 历史文章
permalink: /archive/
---



<ul>
{% for post in site.posts %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <h2>{{ post.date | date: '%Y' }}</h2> 
  {% endif %}
  <li>
    <span class="posts-list-meta">{{ post.date | date:"%Y-%m-%d" }}</span>
    <a class="posts-list-name" href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li> 
{% endfor %}
</ul>