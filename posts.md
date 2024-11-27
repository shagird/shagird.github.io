---
layout: page
# title: Posts
permalink: /posts/
---

{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}

{% for year in postsByYear %}
<h2>{{ year.name }}</h2>

{% for post in year.items %}
<div class="post-item">
  <span class="post-date">{{ post.date | date: "%b %d" }}</span>
  <a href="{{ post.url }}" class="post-link">{{ post.title }}</a>
</div>
{% endfor %}

{% endfor %}