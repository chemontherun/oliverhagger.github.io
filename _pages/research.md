---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

All work in the following is unpublished work by Oliver Hagger. 
All downloadable pdfs are password protected. For access, please email - <a href="mailto:oliver.hagger.21@ucl.ac.uk">here</a>


<h3>A review of the crystal sponge method</h3>
<p>Supervisor: Professor Simon Coles</p>

<a href="/files/4th year project.pdf">Download here</a>


<img src="/images/thyearproject.PNG" alt="Sample of 4th year project report" width="600" height="400"/>
<figcaption>Preview of report</figcaption>




<h3>Calcium based Metal-Organic Frameworks (MOF) derived from CaCO3 precursor particles</h3>
<p>Supervisor: Professor Darren Bradshaw</p>

<a href="/files/3rd year project.pdf">Download here</a>

<img src="/images/rdyearproject.PNG" alt="Sample of 3rd year project report" width="600" height="400"/>






{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}