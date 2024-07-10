---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<hr>

<table style="background-color: transparent; border-collapse: collapse; border: none; width: 100%;border-spacing: 0 100px;">
  <tr style="padding: 50px 0;">
  <td style="width: 75%; border: none;padding-top: 10px;font-size: 20px;">
  
  <h2><b>Rapid single step atmospheric pressure plasma jet deposition of a SERS active surface</b></h2>
  <p style ="line-height:150%"><h4><i>Hagger, O. S. J., et al., Mater. Adv., 2023, Advance Article</i></h4>
  <h4><i>Link to article: <a href= "https://doi.org/10.1039/D3MA00249G">https://doi.org/10.1039/D3MA00249G</a></i></h4></p>
  
  
  </td>
  <td style="border: none; font-size: 20px;padding-left: 10px;padding-top: 10px;"><a href="/images/Cover2.pdf" target="_blank" width="300" height="200">
      <img src="/images/Cover2.pdf" id="myImg2" alt="Graphical Abstract" width="300" height="200" style="float:right; vertical-align: middle;"/>
    </a></td>
  </tr>


</table>
<hr>

<table style="background-color: transparent; border-collapse: collapse; border: none; width: 100%;border-spacing: 0 100px;">
  <tr style="padding: 50px 0;">
  <td style="width: 75%; border: none;padding-top: 10px;font-size: 20px;">
  
  <h2><b>Atmospheric Pressure Plasma Jet Synthesis and Characterization of Copper-Silver Bimetallic Materials as Electrocatalysts for CO2 Reduction</b></h2>
  <p style ="line-height:150%"><h4><i>Agrotis, S., Hagger, O. S. J., et al., Applied Materials Today, 2024, 39, 102286</i></h4>
  <h4><i>Link to article: <a href= "https://doi.org/10.1016/j.apmt.2024.102286">https://doi.org/10.1016/j.apmt.2024.102286</a></i></h4></p>
  
  
  </td>
  <td style="border: none; font-size: 20px;padding-left: 10px;padding-top: 10px;"><a href="/images/Cover3.gif" target="_blank" width="300" height="200">
      <img src="/images/Cover3.gif" id="myImg2" alt="Graphical Abstract" width="300" height="200" style="float:right; vertical-align: middle;"/>
    </a></td>
  </tr>


</table> 
<hr>
<table style="background-color: transparent; border-collapse: collapse; border: none; width: 100%;border-spacing: 0 100px;">
  <tr style="padding: 50px 0;">
  <td style="width: 75%; border: none;padding-top: 10px;font-size: 20px;">
  
  <h2><b>Metal Painting by Plasma Jet</b></h2>
  <p style ="line-height:150%"><h4><i>Lockwood Estrin, F., Hagger, O. S. J., et al., Advanced Materials Interfaces, 2024, 2400256</i></h4>
  <h4><i>Link to article: <a href= "https://doi.org/10.1002/admi.202400256">https://doi.org/10.1002/admi.202400256</a></i></h4></p>
  
  
  </td>
  <td style="border: none; font-size: 20px;padding-left: 10px;padding-top: 10px;"><a href="/images/Cover1.pdf" target="_blank" width="300" height="200">
      <img src="/images/Cover1.pdf" id="myImg2" alt="Graphical Abstract" width="300" height="200" style="float:right; vertical-align: middle;"/>
    </a></td>
  </tr>


</table>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.com/citations?user=THn4XlwAAAAJ&hl=en&authuser=3">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
