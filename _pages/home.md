---
layout: archive
auto_profile: true
permalink: /
header:
  image: unsplash-image-7.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"

feature_row:
  - image_path: unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
  - image_path: unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."

---

{% include base_path %}

{% include feature_row %}

<h3 class="archive__subtitle">Recent Posts</h3>

{% for post in site.posts limit:4 %}
  {% include archive-single.html %}
{% endfor %}
