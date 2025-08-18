---
title: blog
permalink: /blog
layout: default
---
## project updates, rambles, and more!

{% for post in site.posts %}
- ### [{{ post.title }} - *{{ post.description }}*]({{ post.url }})
{% endfor %}
