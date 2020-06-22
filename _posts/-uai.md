---
title: 'Learning LWF Chain Graphs: A Markov Blanket Discovery Approach'
description: Uncertainty in Artificial Intelligence \(UAI 2020\) 
background: /assets/img/mb.png
author: [Mohammad Ali Javidian, Marco Valtorta, Pooyan Jamshidi]
categories: [Structure learning, Chain graphs, Markov blanket]
---

## Overview
![Alt Text](https://raw.githubusercontent.com/majavid/structurelearning/master/assets/img/mbcg.gif)
LWF Chain graphs were introduced by Lauritzen, Wermuth and Frydenberg as a generalization of graphical models based on undirected graphs and DAGs. From the causality point of view, in an LWF CG: Directed edges represent direct causal effects. Undirected edges represents causal effects due to **interference**, which occurs when an individual's outcome is influenced by their social interaction with other population members, e.g., in situations that involve contagious agents, educational programs, or social networks. The construction of chain graph models is a challenging task that would be greatly facilitated by automation. 

**Markov blanket** discovery has an important role in structure learning of Bayesian network. It is surprising, however, how little attention it has attracted in the context of learning LWF chain graphs. In this work,  we provide a graphical characterization of Markov blankets in chain graphs. The characterization is different from the well-known one for Bayesian networks and generalizes it. We provide a novel **scalable** and **sound** algorithm for Markov blanket discovery in LWF chain graphs. We also provide a sound and scalable constraint-based framework for learning the structure of LWF CGs from faithful causally sufficient data. With the use of our algorithm, the problem of structure learning is reduced to finding an efficient algorithm for Markov blanket discovery in LWF chain graphs. This greatly simplifies the structure-learning task and makes a wide range of inference/learning problems computationally tractable because our approach exploit locality. 

## Publication
Mohammad Ali Javidian, Marco Valtorta, and Pooyan Jamshidi. [Learning LWF Chain Graphs: A Markov Blanket Discovery Approach](https://arxiv.org/abs/2006.00970) to appear in **Proceedings of the Thirty Sixth Conference on Uncertainty in Artificial Intelligence (UAI-20)**.

## Code
[MbLWF2020](https://github.com/majavid/MbLWF2020): https://github.com/majavid/MbLWF2020

## Talks
- Mohammad Ali Javidian. Coming soon...

## Future Work
1. Relaxing the faithfulness assumption,
2. Addressing the multiple hypotheses testing problem in the small sample case, and
3. Designing an algorithm for learning 'latent variable chain graphs \(segregated graphs\)' to model interference in relational data.

## Acknowledgement
This work has been supported by
- AFRL and DARPA \(FA8750\-16\-2\-0042\),
- ASPIRE grant from the Office of the Vice President for Research at the University of South Carolina.