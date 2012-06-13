---
layout: page
title: Blogs
---
{% include JB/setup %}


{% for post in site.posts %}
  <h3 class="b_title"><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>&nbsp;&nbsp;/<span class="b_date">/&nbsp;&nbsp;&nbsp;{{ post.date | date_to_string }}</span></h3>
{% endfor %}