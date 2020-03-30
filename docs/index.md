---
title: News
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }}</a>
      {{post}}
    </li>
  {% endfor %}
</ul>
