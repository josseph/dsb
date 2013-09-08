---
layout: page
title: 綃業 术业无专攻的家伙
tagline: 
---
{% include JB/setup %}
    
## Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>



