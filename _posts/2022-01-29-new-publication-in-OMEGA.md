---
categories:
  - Publications
tags:
  - publication
  - OMEGA
  - multi-objective
  - optimization
  - gurobi
  - R

---

Our latest paper  entitled "A multi-objective open vehicle routing problem with overbooking: Exact and heuristic solution approaches for an employee transportation problem" that was accepted for publication in the prestigious OMEGA - The International Journal of Management Science is now available online at [here](https://www.sciencedirect.com/science/article/pii/S0305048321001961#!)

We carried out this study with my colleagues at the Department of Industrial Engineering of Hacettepe University. I am very grateful to Professors Murat Caner Testik, Diclehan Tezcaner Öztürk, Ceren Tuncer Sakar, Guldal Guleryuz, and Ozlem Muge Testik for their collaboration.

If you’re interested in learning more about "School/Employment Bus routing problem under scarce resources" this paper may fit well to your interests. I believe the paper has potential to trigger important developments in the field. There are many real-world applications such as air and school bus transportation where overbooking is an important consideration in seat planning. Additionally, there may be situations where the planned capacity must be less  than the actual seat capacity such as in the Covid-19 pandemic. I would like to thank the editors and reviewers of OMEGA for appreciating the value of this paper.

This paper also interesting in terms of the extensive and efficient usage of analytics. More specifically, we program the all experiments using R programming language and solve the mathematical models using the GUROBI Optimizer 9.0 through R 3.5.3. All experiments were performed at the Center for Computational Research of University at Buffalo, on a Dell 32-core computer running Linux Centos 7.5.x with processor Intel Xeon Gold 6130 CPU, 32 x 2.10GHz and 192 GB usable RAM .

## Highlights

I strongly encourage you to read this paper if you are interested in:
 - A real-world open vehicle routing problem where the total seat capacity is limited and the number of passengers using the buses changes daily, and therefore overbooking to buses are allowed,
 - Multi-objective optimization, and investigation of trade-offs between total distance and number of straphangers
 - Mathematical programming as well as heuristic solution approaches.


You may see the abstract below at full paper at [OMEGA's web site](https://www.sciencedirect.com/science/article/pii/S0305048321001961#!). If you have trouble with accessing to the paper, please feel free to contact with me so that I can provide you the full text free of charge.


## Abstract

We address a bus routing problem, where individuals need to be gathered from spatially distributed pickup points and transported to a workplace. The problem is modeled as an open vehicle routing problem. Overbooking is allowed because the total seat capacity of the buses is limited. The problem is treated as a multi-objective optimization problem, where the total distance traveled by the buses and the total number of straphangers in the buses are minimized. We develop a mixed integer programming (MIP) model and employ the -constraint method to generate the Pareto-optimal frontier. Due to the high computational requirements of the exact model, two heuristic approaches are developed: a heuristic algorithm that is based on a cluster-first and route-second algorithm and a multi-objective evolutionary algorithm. We also develop another MIP model that provides an alternative bound to evaluate the quality of the heuristics’ solutions. Experiments on a small and a moderate-sized problem show that the heuristics are fast and approximate the optimal solutions well. The heuristic approaches are then used to solve the actual problem having 103 pickup points, 50 buses and 1986 individuals. A set of approximate solutions whose total transportation distances are at most 14% worse than the best lower bounds are obtained.

## Keywords:
Open vehicle routing problem, Employee transportation, Overbooking, Multi-objective optimization, Mixed integer programming, Heuristics
