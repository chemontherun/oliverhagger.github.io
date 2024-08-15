---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<hr>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Research</title>
    <style>
        .research-container {
            width: 90%;
            margin: 40px auto;
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .research-container hr {
            border: 1px solid #ddd;
            margin: 40px 0;
        }
        .research-intro {
            margin-bottom: 40px;
            font-size: 16px;
            color: #333;
        }
        .research-intro a {
            color: #0073e6;
            text-decoration: none;
            font-weight: bold;
        }
        .research-intro a:hover {
            text-decoration: underline;
        }
        .research-section {
            margin-bottom: 40px;
        }
        .research-section h3 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #222;
            text-decoration: underline;
        }
        .research-section p {
            margin-bottom: 10px;
            font-size: 18px;
            color: #555;
        }
        .research-section a {
            color: #0073e6;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            margin-bottom: 20px;
        }
        .research-section a:hover {
            text-decoration: underline;
        }
        .research-section img {
            display: block;
            margin: 0 auto;
            border: 1px solid #000;
            border-radius: 8px;
        }
        .research-section figcaption {
            text-align: center;
            margin-top: 10px;
            font-size: 14px;
            color: #777;
        }
    </style>
</head>
<body>

<div class="research-container">
    

    <div class="research-intro">
        All work in the following is unpublished work by Oliver Hagger. 
        All downloadable PDFs are password protected. For access, please <a href="mailto:ohagger@icloud.com">email</a>.
    </div>

    <hr>

    <div class="research-section">
        <h3>A review of the crystal sponge method</h3>
        <p>Supervisor: Professor Simon Coles</p>
        <a href="/files/4th year project.pdf" target="_blank" rel="noopener noreferrer">Download here</a>
        <p><img src="/images/thyearproject.PNG" class="img" alt="Sample of 4th year project report" width="600" height="400"/></p>
        <figcaption>Preview of the report</figcaption>
    </div>

    <hr>

    <div class="research-section">
        <h3>Calcium based Metal-Organic Frameworks (MOF) derived from CaCO<sub>3</sub> precursor particles</h3>
        <p>Supervisor: Professor Darren Bradshaw</p>
        <a href="/files/3rd year project.pdf" target="_blank" rel="noopener noreferrer">Download here</a>
        <p><img src="/images/rdyearproject.PNG" class="img" alt="Sample of 3rd year project report" width="600" height="400"/></p>
        <figcaption>Preview of the report</figcaption>
    </div>

    <hr>

    {% if author.googlescholar %}
      <p class="research-intro">You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u></p>
    {% endif %}

    {% include base_path %}

    {% for post in site.research reversed %}
      {% include archive-single.html %}
    {% endfor %}

</div>

</body>
</html>

<!-- 
All work in the following is unpublished work by Oliver Hagger. 
All downloadable pdfs are password protected. For access, please <a href="mailto:ohagger@icloud.com">email</a>


<h3>A review of the crystal sponge method</h3>
<p>Supervisor: Professor Simon Coles</p>

<a href="/files/4th year project.pdf" target="_blank" rel="noopener noreferrer">Download here</a>


<p align="center"><img src="/images/thyearproject.PNG" class="img" alt="Sample of 4th year project report" width="600" height="400" style='border:1px solid #000000;'/></p>
<figcaption>Preview of the report</figcaption>




<h3>Calcium based Metal-Organic Frameworks (MOF) derived from CaCO3 precursor particles</h3>
<p>Supervisor: Professor Darren Bradshaw</p>

<a href="/files/3rd year project.pdf" target="_blank" rel="noopener noreferrer">Download here</a>

<p align="center"><img src="/images/rdyearproject.PNG" class="img" alt="Sample of 3rd year project report" width="600" height="400" style='border:1px solid #000000'/></p>
<figcaption>Preview of the report</figcaption>





{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %} -->