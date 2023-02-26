---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---
My academic research falls into two main areas: Statistical Machine Learning and Data Scienlce in Finance, with 
a focus on Financial Time-Series Analysis and Risk Analysis. 
I am particularly interested in using advanced mathematical and computational techniques to analyse
and model financial data, with the goal of better understanding and predicting market trends and risks. 

My other research includes applied linear mathematics in cryptography and mathematics education system.

Currently, I am working as a Research Assistant at UNMC, designing algorithmatic mathematics assessment for
undergraduate mathematics students.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
