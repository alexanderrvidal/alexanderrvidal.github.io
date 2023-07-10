---
title: "Taming hyperparameter tuning in continuous normalizing flows using the JKO scheme"
collection: publications
permalink: /publications/articles/vidaltaming-2023
citation: "<b>Vidal, Alexander</b>, Wu Fung, Samy, Tenorio, Luis, Osher, Stanley, Nurbekyan, Levon: <i>&quot;Taming hyperparameter tuning in continuous normalizing flows using the JKO scheme&quot;</i>, Scientific Reports, DOI: <a href='https://www.nature.com/articles/s41598-023-31521-y'>https://www.nature.com/articles/s41598-023-31521-y</a>, 2023."
date: 2023-03-18
venue: Scientific Reports
---
## Abstract
A normalizing flow (NF) is a mapping that transforms a chosen probability distribution to a normal distribution. Such flows are a common technique used for data generation and density estimation in machine learning and data science. The density estimate obtained with a NF requires a change of variables formula that involves the computation of the Jacobian determinant of the NF transformation. In order to tractably compute this determinant, continuous normalizing flows (CNF) estimate the mapping and its Jacobian determinant using a neural ODE. Optimal transport (OT) theory has been successfully used to assist in finding CNFs by formulating them as OT problems with a soft penalty for enforcing the standard normal distribution as a target measure. A drawback of OT-based CNFs is the addition of a hyperparameter, 𝛼, that controls the strength of the soft penalty and requires significant tuning. We present JKO-Flow, an algorithm to solve OT-based CNF without the need of tuning 𝛼. This is achieved by integrating the OT CNF framework into a Wasserstein gradient flow framework, also known as the JKO scheme. Instead of tuning 𝛼, we repeatedly solve the optimization problem for a fixed 𝛼 effectively performing a JKO update with a time-step 𝛼. Hence we obtain a ”divide and conquer” algorithm by repeatedly solving simpler problems instead of solving a potentially harder problem with large 𝛼.
