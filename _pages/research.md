---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

All work in the following is unpublished work by Oliver Hagger. 
All downloadable pdfs arepassword protected. For access to any of the files, please email - <a href="oliver.hagger.21@ucl.ac.uk">Oliver Hagger</a>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}