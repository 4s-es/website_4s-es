---
permalink: /news-x/
title: News
subtitle: Four Stars Engineering Systems (FourStars-ES)
layout: blog
sort: title
show_sidebar: false
image: /assets/img/bg/4ses.jpg
hero_image: /assets/img/bg/4ses.jpg
hero_darken: true
---
{% for post in site.posts offset:1 limit:99999 %}
<ul>
  <article>
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
<blogspan>{{ post.excerpt }}</blogspan>
  </article>
</ul>
{% endfor %}
