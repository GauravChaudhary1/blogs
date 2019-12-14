---
layout: archive
permalink: /machine-learning/
title: "Machine Learning"
author_profile: true
header: 
    image: "images/waterfront.jpg"
---
{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}