---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

All work in the following is unpublished work by Oliver Hagger. 
All downloadable pdfs are password protected. For access, please email - <a href="mailto:oliver.hagger.21@ucl.ac.uk">here</a>

Title:
A REVIEW OF THE CRYSTAL SPONGE METHOD
------
Abstract
------
There is an ability of [(ZnI2)3(TPT)2·x(solvent)]n to form a crystal sponge. This crystalsponge can be used to analyse non-crystalline compounds by single-crystal X-raydiffraction (SCXRD). First, the investigation to the repeatability of the procedurereported by Fujita et al. to show the ease of reproducibility. The crystals began to crackduring the solvent exchange step of the procedure presented by Fujita et al., different
variables were investigated to stop this cracking of the crystals. With reproducing the
crystal sponges, it was found the crystal began to ‘die’ as a result of bombardment by
X-rays. This ‘dying’ would then render the sponge useless. How quickly the crystals
were ‘dying’ was then investigated carried out at Diamond Light Source, Oxford.

<img src="/images/thyearproject.PNG" alt="Sample of 4th year project report" width="600" height="400"/>

<img src="/images/rdyearproject.PNG" alt="Sample of 3rd year project report" width="600" height="400"/>




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}