---
layout: page
title: About
permalink: /about/
---

<div class="about-images">
    {% for image in site.static_files %}
      {% if image.path contains 'about' %}
        <img class="about-image" src="{{ site.url }}{{ image.path }}">
      {% endif %}
    {% endfor %}
</div>

<p>
Hi, I'm James, a software engineer and Wushu (Chinese Martial Arts) enthusiast from and currently residing in the San Francisco Bay Area.
My dedication to Wushu and programming were initiated during my years at UCLA.
I created this website to store my thoughts and content in both realms.
<br><br>
If my talents can be of use to you, <a href="mailto:{{ site.email }}"> let's talk</a>.
</p>

