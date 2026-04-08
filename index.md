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

## Focus

I examine power, institutions, and society through clear, structured writing.

This is not casual blogging. It is deliberate thinking made public.

---

## Sections

- Essays → Long-form arguments and analysis  
- Notes → Short reflections and observations  
- Photos → Visual documentation  

---

## Latest Writing

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
