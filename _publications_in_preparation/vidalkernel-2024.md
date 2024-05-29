---
title: "Kernel Expansions for High-Dimensional Mean-Field Control with Non-local Interactions"
collection: publications_in_preparation
permalink: /publications_in_preparation/articles/vidalkernel-2024
citation: "<b> Vidal, Alexander </b>, Wu Fung, Samy, Tenorio, Luis, Osher, Stanley, Nurbekyan, Levon. <i>&quot;Kernel Expansions for High-Dimensional Mean-Field Control with Non-local Interactions&quot;</i>,arXiv preprint arXiv:2405.10922, DOI: <a href='https://arxiv.org/abs/2405.10922'>https://arxiv.org/abs/2405.10922</a>, 2024."
Date: 2024-5-17
venue: 'arXiv preprint arXiv:2405.10922'
---
## Abstract
Mean-field control (MFC) problems aim to find the optimal policy to control massive populations of interacting agents. 
These problems are crucial in areas such as economics, physics, and biology. 
We consider the non-local setting, where the interactions between agents are governed by a suitable kernel. For $N$ agents, the interaction cost has $\mathcal{O}(N^2)$ complexity, which can be prohibitively slow to evaluate and differentiate when $N$ is large.
To this end, we propose an efficient primal-dual algorithm that utilizes basis expansions of the kernels. The basis expansions reduce the cost of computing the interactions, while the primal-dual methodology decouples the agents at the expense of solving for a moderate number of dual variables. 
We also demonstrate that our approach can further be structured in a multi-resolution manner, where we estimate optimal dual variables using a moderate $N$ and solve decoupled trajectory optimization problems for large $N$. We illustrate the effectiveness of our method on an optimal control of 5000 interacting quadrotors (see GIF).


<iframe src="https://giphy.com/embed/UngFIy49DnJsemDYbW" width="480" height="360" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/UngFIy49DnJsemDYbW"></a></p>
