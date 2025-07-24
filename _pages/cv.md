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
- **Ph.D. in Applied Mathematics and Statistics**, 2019-May 2024<br>
**[Department of Applied Mathematics and Statistics](https://ams.mines.edu/ "https://ams.mines.edu/"), [Colorado School of Mines](https://www.mines.edu/ "https://www.mines.edu/")**
  - *Thesis:* [Deep Learning Methods for Large-Scale Physics]()
  - *Committee:* [Dr. Samy Wu Fung (Advisor)](https://ams.mines.edu/project/wu-fung-samy/), [Dr. Luis Tenorio (Advisor)](https://ams.mines.edu/project/tenorio-luis/), [Dr. Gregory Fasshauer](https://ams.mines.edu/project/fasshauer-greg/), [Dr. Douglas Nychka](https://ams.mines.edu/project/nychka-doug/), [Dr. Levon Nurbekyan](https://sites.google.com/view/lnurbek/home), [Dr. Thomas Monecke (Chair)](https://geology.mines.edu/project/monecke-thomas/)

- **M.Sc. in Applied Mathematics and Statistics, Minor: Electrical Engineering**, 2018-2019<br>
**[Department of Applied Mathematics and Statistics](https://ams.mines.edu/ "https://ams.mines.edu/"), [Colorado School of Mines](https://www.mines.edu/ "https://www.mines.edu/")**

- **B.Sc. in Engineering, Minor: Economics**, 2006-2010<br>
**[University of Colorado - Boulder](https://www.colorado.edu/ "https://www.colorado.edu/")**

## Experience

- **Senior Machine Learning Researcher**, [Launch Potato](https://www.launchpotato.com), February 2025 – Present  
  - *Location:* Remote / Durango, CO  
  - **Technical Leadership:** Serve as the primary machine learning expert across all business verticals. Mentor fellow data scientists and lead strategic ML initiatives, particularly in recommendation systems.  
  - **Recommendation Systems:** Identify opportunities for ranking and personalization (e.g., two-tower architectures). Lead technical implementation and contribute to engineering and MLOps.  
  - **Revenue Optimization:** Develop utility-aware models to optimize revenue per click (RPC), bid adjustments, and downstream monetization strategies.  
  - **Learning with Bandits:** Apply contextual and multi-armed bandits to optimize ad placement and recommendation performance under uncertainty.  
  - **Statistical Inference:** Conduct A/B tests and use statistical methods to quantify the effectiveness of ML-driven interventions.


- **Senior Data Scientist**, On The Barrelhead / [NerdWallet](https://www.nerdwallet.com), October 2021 – August 2024  
  - *Location:* Remote / Durango, CO  
  - **Technical Leadership:** Led the data science team for Credit Cards and Lending, mentoring a direct report and driving strategic machine learning initiatives.  
  - **Startup Transition:** Spearheaded the integration of On The Barrelhead’s data science operations into NerdWallet post-acquisition, enhancing ML capabilities across product pages.  
  - **Revenue Growth:** Designed and deployed recommendation algorithms for product roundups, increasing average revenue per session by 15%.  
  - **Synthetic Data Generation:** Leveraged generative modeling to augment class-imbalanced datasets, improving ML performance in key applications.  
  - **User Engagement Optimization:** Developed predictive models for personalized product recommendations, increasing click-through rates by 10%.  
  - **Risk Management:** Applied portfolio optimization techniques to determine the ideal product mix, balancing risk and user value.
 
- **Chief Data Scientist**, [Rigorous Machine Learning Solutions, LLC](), October 2022 - Present
  * Consulted on predictive data modeling projects for [Regenexx](https://www.regenexx.com/), [Verra](https://www.verra.ai/), and On The Barrelhead (before starting full-time as a senior data scientist).

- **National Science Foundation (NSF) Intern, USGS**, June 2021-August 2021
  * Worked with the USGS hyperspectral team to collect hyperspectral data for more accurate predictive analysis.

- **Graduate Research Assistant**, [CASERM](https://caserm.mines.edu/), 2019 - 2021
  * Collected two different types of mineralogical data and applied image recognition techniques in order to
reconcile the two datasets.
  * A preprocessing step was applied that uses convolutional neural networks to "mask” the data that is not useful.
  * A stochastic autoencoder (SAE) is used to 'mix' the data used from different sources a latent space.
  * Neural network is used to allow for prediction of one dataset given the other.

- **Data Science Intern**, [Lumen Technologies (formerly CenturyLink)](https://www.lumen.com/), June 2019 - August 2019
  - *Working Group:* Finance
  * Classified pdf documents using deep learning and natural language processing (NLP).
    
- **Teaching Assistant**, [Colorado School of Mines](https://www.mines.edu/), 2018-2021
  * *Classes:* MATH534/535: Mathematical Statistics, MATH537: Multivariate Analysis, MATH536: Advanced Statistical Modeling, MATH225: Differential Equations.
  
## Computer Skills
- **Programming languages:** Python, R, Matlab, Bash/Shell script, LaTeX, PostgreSQL, MSSQL
- **Packages:** Numpy, Scipy, Pandas, scikit-learn, Pytorch, Keras, Tensorflow, CVX, CVXPy
- **Operating Systems:** MacOS, Linux, Windows
- **Other:** Git

## Software Publications and Contributions

- **Python:** [Kernel Expansions for MFC](https://github.com/mines-opt-ml/kernel-expansions-for-mfc) (Pytorch implementation for MFC paper)
- **Python:** [JKO-Flow](https://github.com/mines-opt-ml/JKO_Flow) (Pytorch implementation for the JKO-Flow paper)

## Peer-Reviewed Publications
<ul>{% for post in site.publications reversed %}
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

