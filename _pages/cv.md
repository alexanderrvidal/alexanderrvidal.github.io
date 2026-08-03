---
permalink: /cv/
title: "Curriculum Vitae"
excerpt: "Education, teaching experience, research, publications, and technical background."
author_profile: true
redirect_from:
  -
---

{% include base_path %}

<!--
Click [here](/cv-print/) for a printable version or
[download a PDF](/files/cv-print.pdf).
-->

<h2 align="center">{{ site.author.name }}</h2>

<p align="center" style="margin: auto; width: 80%;">
  {{ site.author.bio }}
</p>

<p align="center">
  <br>
  <i class="fas fa-envelope" aria-hidden="true"></i>&nbsp;
  <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>
  &nbsp;|&nbsp;
  <a href="https://www.alexander-vidal.com">www.alexander-vidal.com</a>
  &nbsp;|&nbsp;
  <a href="{{ site.author.googlescholar }}">Google Scholar</a>
</p>


## Education

### Ph.D. — Applied Mathematics and Statistics

**Colorado School of Mines**  
December 2024

- **Thesis:** *Deep Learning Methods for Large-Scale Physics*
- **Advisors:** [Dr. Samy Wu Fung](https://ams.mines.edu/project/wu-fung-samy/) and [Dr. Luis Tenorio](https://ams.mines.edu/project/tenorio-luis/)
- **Committee:** [Dr. Levon Nurbekyan](https://sites.google.com/view/lnurbek/home), [Dr. Gregory Fasshauer](https://ams.mines.edu/project/fasshauer-greg/), [Dr. Thomas Monecke](https://geology.mines.edu/project/monecke-thomas/), and [Dr. Douglas Nychka](https://ams.mines.edu/project/nychka-doug/)
- Magna Cum Laude, GPA: 3.8/4.0


### M.Sc. — Applied Mathematics and Statistics

**Colorado School of Mines**  
May 2020

- Magna Cum Laude, GPA: 3.8/4.0


### B.Sc. — Mechanical Engineering, Minor: Economics

**University of Colorado Boulder**


## Teaching & Instructional Experience

### Teaching Assistant

**Colorado School of Mines** — Golden, CO  
August 2018 – May 2022

- Delivered instructional support, hosted tutoring sessions, and graded evaluations for the following advanced undergraduate and graduate-level courses:
  - MATH534/535: Mathematical Statistics (Probability)
  - MATH530/531: Statistical Methods
  - MATH537: Multivariate Analysis
  - MATH536: Advanced Statistical Modeling
  - MATH225: Differential Equations


### Teaching Assistant

**University of Colorado Boulder** — Boulder, CO  
August 2010 – December 2010

- Served as the lab teaching assistant, providing in-person technical instruction and assistance to students working on assignments for the following course:
  - MCEN4037: Experimental Design and Data Analysis


## Expertise & Skills

- **Mathematics & Statistics:** Probability, Multivariate Analysis, Differential Equations, Calculus, Linear Algebra
- **Mathematical Modeling:** Numerical Optimization, Scientific Computing
- **Machine Learning:** Deep Learning, Generative Modeling (Diffusion/Normalizing Flows), Ranking
- **Programming Languages:** Python, R, MATLAB, SQL, Bash/Shell Script, LaTeX
- **Libraries & Tools:** PyTorch, TensorFlow, XGBoost, NumPy, Pandas, Polars, Scikit-Learn, Git


## Industry and Technical Experience

<!--
Add the Denver Life Sciences consulting role here after confirming
the exact job title, start date, and final CV wording.
-->

### Owner and Machine Learning Scientist

**[Rigorous Machine Learning Solutions, LLC]()** — Remote/Durango, CO  
October 2020 – Present

- Advised diverse industry clients on end-to-end predictive data modeling architectures and taught teams how to integrate statistical frameworks into existing infrastructures.
- Designed custom machine learning models to solve specialized client issues, transforming raw mathematical principles into robust algorithmic deployments.


### Senior Machine Learning Researcher

**[Launch Potato](https://www.launchpotato.com)** — Remote/Durango, CO  
February 2025 – June 2026

- Served as the primary machine learning technical resource across multiple business verticals, focusing on mentoring data scientists and translating complex mathematical models for engineering teams.
- Led the end-to-end design and deployment of large-scale mathematical recommendation architectures.
- Utilized rigorous A/B testing frameworks and statistical inference to evaluate model efficacy, communicate findings, and guide data-driven strategy.


### Senior Data Scientist

**On The Barrelhead / [NerdWallet](https://www.nerdwallet.com)** — Remote/Durango, CO  
October 2021 – August 2024

- Supervised the data science division for credit cards and lending, providing direct professional mentorship, training, and academic direction to junior researchers.
- Directed the complex technical integration of machine learning operations following corporate acquisition, clarifying mathematical optimization strategies to cross-functional stakeholders.
- Formulated personalized predictive models and deployed portfolio optimization techniques to balance risk matrices against core system utilities.


### National Science Foundation (NSF) Intern

**United States Geological Survey** — Remote/Lakewood, CO  
Summer 2021

- Partnered with the USGS hyperspectral research branch to model and parse hyperspectral datasets, establishing predictive analyses for planetary geology.


### Graduate Research Assistant

**[Center for Advanced Subsurface Earth Resource Models](https://caserm.mines.edu/)** — Remote/Golden, CO  
August 2019 – August 2021

- Developed image recognition and computer-vision workflows to isolate anomalies and cross-verify distinct mineralogical datasets.
- Built convolutional neural networks and stochastic autoencoders to project distinct physical parameters into a shared mathematical latent space.


### Data Science Intern

**[Lumen Technologies](https://www.lumen.com/) (formerly CenturyLink)** — Remote/Broomfield, CO  
Summer 2019

- Applied natural language processing architectures and deep learning classifiers to automate document indexing and classification.


## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>


## Academic Service

- Reviewer, IEEE American Control Conference (ACC 2026)


## Open-Source Software

- **[Kernel Expansions for Mean-Field Control](https://github.com/mines-opt-ml/kernel-expansions-for-mfc):** Implementation of the ACC (2025) paper
- **[JKO-Flow: Normalizing Flows via the JKO Scheme](https://github.com/mines-opt-ml/JKO_Flow):** Implementation of the Scientific Reports (2023) paper


## Select Conference Contributions and Talks

<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>
