---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<hr>

<table style="background-color: transparent; border-collapse: collapse; border: none; width: 100%;border-spacing: 0 150px;">
  <tr style="padding: 100px 0;">
  <td style="width: 50%; border: none;padding-top: 10px;font-size: 20px;">
  
  <h1>Rapid single step atmospheric pressure plasma jet deposition of a SERS active surface</h1>
  <h3>Hagger, O. S. J., et al., Mater. Adv., 2023, Advance Article</h3>
  <h3>Link to article: <a href= "https://doi.org/10.1039/D3MA00249G">Advance Materials</a></h3>
  
  
  </td>
  <td style="border: none; font-size: 20px;padding-left: 10px;padding-top: 10px;"><a href="/images/Paper_graphical_abstract2.png" target="_blank" width="300" height="200">
      <img src="/images/Paper_graphical_abstract2.png" id="myImg2" alt="Graphical Abstract" width="300" height="200" style="float:right; vertical-align: middle;"/>
    </a></td>
  <td></td>
  </tr>


</table>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
