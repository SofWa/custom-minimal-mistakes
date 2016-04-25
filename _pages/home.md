---
title: welcome
layout: archive
permalink: /
header:
  image: unsplash-image-7.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---

{% include base_path %}

<h3 class="archive__subtitle">Recent Posts</h3>

{% for post in paginator.posts limit 5 %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
