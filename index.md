---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

<div class="list-group">
  {% for post in site.posts %}
    <a href="{{ post.url }}" class="list-group-item">
      <h4 class="list-group-item-heading">{{ post.title }}</h4>
      <p class="list-group-item-text">{{ post.excerpt }}</p>
    </a>
  {% endfor %}
</div>
