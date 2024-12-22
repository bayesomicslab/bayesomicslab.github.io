---
title: Home
---

# Blending algorithms and Bayesian machine learning in computational biology.

The Efficient Learning and Graph Algorithm Techniques for Omics (EL GATO) Lab at UConn was founded in 2018 and includes researchers with a wide range of interests and specialties. Our research aims to develop probabilistic machine learning models, combinatorial algorithms, and scalable inference methods to better understand high-dimensional data, particularly genomics and genetics data applied to complex disease. 

{% include section.html full=false %}

{%
  include figure.html
  image="images/elgato_lab_2024.jpg"
  caption="EL GATO Lab and Friends at our 2024 BBQ"
  link="team"
  width="100%"
%}

{% include section.html %}


## Some recent news

{%
  include list.html
  data="news"
  component="card"
  filter="date.between?('2020', '2025')"
  style="small"
%}


{% include section.html %}

{% capture text %}
We focus on Bayesian machine learning and combinatorial methods development across a wide range of areas. 

{:.center}
{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}

{:.center}
{%
  include link.html
  link="publications"
  text="See publications"
  icon="fas fa-arrow-right"
  flip=true
%}

{:.center}
{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}

{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/bamie.png"
  link="research"
  title="Our Research"
  text=text
%}

