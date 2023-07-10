---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<hr>

<table style="background-color: transparent; border-collapse: collapse; border: none; width: 100%;border-spacing: 0 150px;">
  <tr style="padding: 100px 0;">
  <td style="width: 50%; border: none;padding-top: 20px;font-size: 20px;">Rapid single step atmospheric pressure plasma jet deposition of a SERS active surface</td>
  <td style="border: none; font-size: 20px;padding-left: 40px;padding-top: 20px;"><a href="/images/graphical_abstract2.png" target="_blank" width="300" height="200">
      <img src="/images/graphical_abstract2.png" id="myImg2" alt="Tableau Dashboard" width="300" height="200" style="float:right; vertical-align: middle;"/>
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
