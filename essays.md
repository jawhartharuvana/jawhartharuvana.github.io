---
layout: default
title: Essays
---

<div class="container">

  <h1>Essays</h1>

  <ul class="posts">
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <span class="date">{{ post.date | date: "%b %d, %Y" }}</span>
      </li>
    {% endfor %}
  </ul>

</div>
