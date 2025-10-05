---
layout: page
title: Blog
permalink: /blog/
---

<div class="post-list" markdown="1">
{% for post in site.posts %}

{{ post.date | date: "%Y-%m-%d" }} — **[{{ post.title }}]({{ post.url }})**

{% endfor %}
</div>
