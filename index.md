---
layout: page
title: 'Recent Posts'
---
{% include JB/setup %}

<ul class="posts recent">
  {% for post in site.posts limit:5 %}
    <li>
        <span class="date">{{ post.date | date_to_string }}</span>
        <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
        <span class="author"> by {{ post.author }}</span>
    </li>
  {% endfor %}
</ul>
