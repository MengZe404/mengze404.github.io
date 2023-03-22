---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---
My research interests fall into two main areas: Machine Learning and Data Science, with various topics such as:
- Federated Learning
- NLP (Semantic Analysis and Personalization)
- Time-Series Forecasting with Neural Network
- Statistical Machine Learning (heterogeneity diagnostic)
- 
I am interested in both theoretical studies and practical applications.

My other research includes applied linear algebra, cryptography and mathematics education. Currently, I am working as a Research Assistant at UNMC, designing algorithmic mathematics assessment for
undergraduate mathematics students. 

In the meantime, I have been invited by the school to give several research-sharing talks, and my work and efforts have been well-recognized by all staff and students.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
