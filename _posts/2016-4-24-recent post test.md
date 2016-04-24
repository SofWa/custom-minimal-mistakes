---
title:  "Recent Post Test!!"
categories: 
  - test

author_profile: false
sidebar:
  - title: "Title"
    image: http://placehold.it/350x250
    image_alt: "image"
    text: "Some text here."
  - title: "Another Title"
    text: "More text here."
    category: "show"
---

<ul>
{% for post in site.categories[category_name] %}
    <li>{{ post.title }}</li>
{% endfor %}
</ul>
