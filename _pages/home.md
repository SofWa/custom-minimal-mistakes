---
layout: archive
auto_profile: true
permalink: /
header:
  image: https://source.unsplash.com/random/1600x500
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---

{% include base_path %}

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts }}</h3>

{% for post in site.posts limit:4 %}
  {% include archive-single.html %}
{% endfor %}
