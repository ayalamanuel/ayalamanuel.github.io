---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

My research interests span a wide range of topics within [Your Academic Field]. I am particularly intrigued by [Highlight one or more specific research interests or areas you are passionate about]. My goal is to address critical questions and challenges in these areas, fostering a deeper understanding of [Your Academic Field] and its implications for society.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
