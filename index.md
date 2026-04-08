---
layout: default
title: Muhammed Jawhar
---

<div class="hero">
  <img src="/IMG_20260407_083832.png" class="avatar">

  <h1>Muhammed Jawhar</h1>
  <p class="subtitle">
    Political thought. Social analysis. Structured writing.
  </p>

  <div class="actions">
    <a href="#" class="btn primary">Read Essays</a>
    <a href="#" class="btn">Contact</a>
  </div>
</div>

<div class="section grid">
  <div class="card">
    <h3>Focus</h3>
    <p>I examine power, institutions, and society through structured writing.</p>
  </div>

  <div class="card">
    <h3>Work</h3>
    <p>Long-form essays, notes, and visual documentation.</p>
  </div>

  <div class="card">
    <h3>Approach</h3>
    <p>Not blogging. Deliberate thinking made public.</p>
  </div>
</div>

<div class="section">
  <h2>Latest Writing</h2>
  <ul>
    {% for post in site.posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
