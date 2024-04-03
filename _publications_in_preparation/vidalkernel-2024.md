---
title: "Kernel Expansions for Mean-Field Control"
collection: publications_in_preparation
permalink: /publications_in_preparation/articles/vidalkernel-2024
citation: "<b> Vidal, Alexander </b>, Wu Fung, Samy, Tenorio, Luis, Osher, Stanley, Nurbekyan, Levon"
venue: 'Coming Soon!'
---
## Abstract
Mean-field control (MFCs) problems aim to find the optimal policy to control massive populations of interacting agents. These problems are crucial in areas such as in economics, physics, and biology. 
We consider the nonlocal setting, where the interaction between agents is defined by a kernel. For $N$ agents, the interaction cost in this case has complexity $\mathcal{O}(N^2)$, which can be prohibitively slow to evaluate (and differentiate) when $N$ is large. We propose a primal-dual based approach that utilizes a basis expansion of the kernel to decouple the interaction term. This decoupling renders computation of the optimal controller parallelizable. We demonstrate the effectiveness of our method on an optimal control of 5000 interacting quadcopters.
