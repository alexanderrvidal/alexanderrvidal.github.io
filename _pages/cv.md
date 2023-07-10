---
permalink: /cv/
title: "Curriculum Vitae"
excerpt: "Education, scientific background, research interests & skills, and more."
author_profile: true
redirect_from:
  -
---

{% include base_path %}

<!-- Click [here](/cv-print/) for a printable version or [download a PDF](/files/cv-print.pdf).<br /><br /><br /> -->

<h2 align="center">{{ site.author.name }}</h2>
<!-- <h3 align="center" style="margin: 0px auto 20px;">M.Sc.</h3> -->
<p align="center" style="margin: auto; width: 80%">{{ site.author.bio }}</p>
<!-- &#124; This symbol is a vertical bar-->

<p align="center"><i class="fas fa-envelope" aria-hidden="true"></i>&nbsp;<a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a> </p>

## Education
- **Ph.D. in Applied Mathematics and Statistics**, 2019-Current<br>
**[Department of Applied Mathematics and Statistics](https://ams.mines.edu/ "https://ams.mines.edu/"), [Colorado School of Mines](https://www.mines.edu/ "https://www.mines.edu/")**
  - *Thesis:* [DEEP LEARNING APPROACHES TO OPTIMAL TRANSPORT AND OPTIMAL CONTROL]()
  - *Committee:* [Dr. Samy Wu Fung (Advisor)](https://ams.mines.edu/project/wu-fung-samy/), [Dr. Luis Tenorio (Advisor)](https://ams.mines.edu/project/tenorio-luis/), [Dr. Gregory Fasshauer](https://ams.mines.edu/project/fasshauer-greg/) [Dr. Douglas Nychka](https://ams.mines.edu/project/nychka-doug/), [Dr. Thomas Monecke (Chair)](https://geology.mines.edu/project/monecke-thomas/)

- **M.Sc. in Appllied Mathematics and Statistics, Minor: Electrical Engineering**, 2018-2019<br>
**[Department of Applied Mathematics and Statistics](https://ams.mines.edu/ "https://ams.mines.edu/"), [Colorado School of Mines](https://www.mines.edu/ "https://www.mines.edu/")**

- **B.Sc. in Engineering, Minor: Economics**, 2006-2010<br>
**[University of Colorado - Boulder](https://www.colorado.edu/ "https://www.colorado.edu/")**

## Experience
- **Senior Data Scientist**, [On The Barrelhead / NerdWallet](www.nerdwallet.com), October 2021 - Present

  - *Working group:* Credit Cards and Lending
 
- **Chief Data Scientist**, [Rigorous Machine Learning Solutions, LLC](), October 2022 - Present

  * Consulted on various contract projects.

- **Graduate Research Assistant**, [CASERM](https://caserm.mines.edu/), 2019 - 2021

  * Worked on a project that requires collecting two different types of mineralogical data and applying image recognition techniques in order to
reconcile the two datasets. A preprocessing step is applied that uses convolutional neural networks to "mask” the data that is not useful. Following the preprocessing, neural network modeling are used to allow for prediction of one dataset given the other.

- **Data Science Intern**, [Lumen Technologies (formerly CenturyLink)](https://www.lumen.com/), June 2019 - August 2019

  - *Working Group:* Finance

- **Teaching Assistant**, [Colorado School of Mines](https://www.mines.edu/), 2018-2020


## Computer Skills
- **Programming languages:** R, Python, Matlab, C++, Bash/Shell script, LaTeX, PostgreSQL, MSSQL
- **Packages:** Numpy, Scipy, Pandas, scikit-learn, Pytorch, Keras, Tensorflow, ggplot2, dplyr, cartopy, netCDF4, dask, xarray
- **Other:** Git

## Software Publications and Contributions

- **Python:** [JKO_flow](https://github.com/mines-opt-ml/JKO_Flow) (Pytorch implementation for the JKO-Flow paper)

## Peer-Reviewed Publications
<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>

## Technical Reports
<ul>{% for post in site.publications_technotes reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>

## Poster Publications
<ul>{% for post in site.publications_posters reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>

## Manuscripts in Preparation and Preprints
<ul>{% for post in site.publications_in_preparation reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>

## Conference Contributions & Talks
<ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

## Teaching
<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>
