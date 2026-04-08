---
layout: default
title: Muhammed Jawhar
---

<div class="hero">
  <img src="/IMG_20260407_083832.png" class="profile">
  <p class="tagline">
    Political thought. Social analysis. Structured writing.
  </p>
</div>

<div class="section">
  <h2>Focus</h2>

  <p>
    I examine power, institutions, and society through clear, structured writing.
  </p>

  <p>
    This is not casual blogging. It is deliberate thinking made public.
  </p>
</div>

<div class="section">
  <h2>Sections</h2>

  <ul>
    <li>Essays → Long-form arguments and analysis</li>
    <li>Notes → Short reflections and observations</li>
    <li>Photos → Visual documentation</li>
  </ul>
</div>

<div class="section">
  <h2>Latest Writing</h2>

  <ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  </ul>
</div>
