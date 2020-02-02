---
layout: archive
title: "Data Science Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

## Data Science projects with R

Portfolio of data science projects using R and Jupyter notebooks demonstrating the usage of data cleaning, manipulation, exploration, visualization, and modeling on a variety of datasets. Each folder contains a standalone project with datasets and a notebook with real-world applications. These guided projects from Datacamp.com have been worked on independently and the solutions are not provided by DataCamp.


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

