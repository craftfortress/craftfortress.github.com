---
layout: page
title: @craftfortress
tagline: Blog
---
{% include JB/setup %}

Portfolio : [Craftfortress.com](http://jwww.craftfortress.com)

Tweet me : [@craftfortress](http://twitter.com/craftfortress)

Email : chris craftfortress.com
 
    
## Archive

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
 


