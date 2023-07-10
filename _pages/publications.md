---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<hr>

<table>
  <tr>
  <td>Rapid single step atmospheric pressure plasma jet deposition of a SERS active surface</td>
  <td style="border: none; font-size: 20px;padding-left: 40px;padding-top: 20px;"><a href="/images/graphical_abstract.png" target="_blank" width="300" height="200">
      <img src="/images/graphical_abstract.png" id="myImg2" alt="Tableau Dashboard" width="300" height="200" style="float:right; vertical-align: middle;"/>
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
