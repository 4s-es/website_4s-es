---
id: 43
title: 'News'
permalink: /news/index.html
date: '2012-04-25T15:04:12+00:00'
author: CP
layout: default
---
{% for post in site.posts offset:1 limit:99999 %}
<ul>
  <article>
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
{{ post.excerpt }}
  </article>
</ul>
{% endfor %}
