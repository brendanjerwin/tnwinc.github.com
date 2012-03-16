---
layout: page
title: 'Recent Posts'
---
{% include JB/setup %}

<ul class="posts recent" id="postsList">
  {% for post in site.posts limit:10 %}
    <li>
        <a href="{{ BASE_PATH }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
        <div>
          {{ post.summary }}
        </div>
    </li>
  {% endfor %}
</ul>
<script>
  Array.prototype.forEach.call(document.getElementById('postsList').getElementsByTagName('LI'), function(li){
    var a = li.getElementsByTagName('A')[0];
    li.onclick = function(){
      window.location = a.href;
    }
  });
</script>
