---
layout: page
title: Welcome!
tagline: Just starting...
---
{% include JB/setup %}

Starting with jekyll is not that difficult, but it's still step by step. So here are my first posts, including the "how to" post jekyll bootstrap provided me with:
    
## Sample Posts


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



