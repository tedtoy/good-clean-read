---
layout: default
---


### thoughts

<div>
  {% for post in site.posts %}
    <div class="post">
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </div>
  {% endfor %}
</div>
