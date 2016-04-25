---
title: welcome
layout: single
permalink: /
header:
  image: unsplash-image-7.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---

<h3 class="archive__subtitle">Recent Posts</h3>

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}
