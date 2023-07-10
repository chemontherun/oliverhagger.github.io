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
  <h4><i>Hagger, O. S. J., et al., Mater. Adv., 2023, Advance Article</i></h4>
  <h4><i>Link to article: <a href= "https://doi.org/10.1039/D3MA00249G">https://doi.org/10.1039/D3MA00249G</a></i></h4>
  
  
  </td>
  <td style="border: none; font-size: 20px;padding-left: 10px;padding-top: 10px;"><a href="/images/Paper_graphical_abstract2.png" target="_blank" width="300" height="200">
      <img src="/images/Paper_graphical_abstract2.png" id="myImg2" alt="Graphical Abstract" width="300" height="200" style="float:right; vertical-align: middle;"/>
    </a></td>
  </tr>


</table>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
