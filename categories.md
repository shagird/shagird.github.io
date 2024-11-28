---
layout: page
# title: Categories
permalink: /categories/
---

<div class="view-options">
  <a href="/posts/">sort posts by dates</a>
</div>

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}