---
layout: work
title: Timber Frames
slug: /timber_frames
---

Timber framing uses a combination of joints such as dovetails, scarf joints, notches and wooden pegs on timbers to form a structure.

{% for project in site.timber_frames %}
## {{ project.title }}

<a href="{{ project.url }}">
  <img src="{{ project.images }}/{{ project.slug }}/{{ project.thumbnail }}" alt="{{ project.title }}" width=200px/>
</a>
{% endfor %}
