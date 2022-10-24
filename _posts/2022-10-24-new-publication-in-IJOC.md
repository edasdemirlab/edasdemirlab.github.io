---
title: "Our New Paper in INFORMS Journal on Computing is Now Available Online"
layout: single
classes: wide
author_profile: true
read_time: true
comments: true
share: true
related: true
show_date: true

excerpt: "Our latest paper in the prestigious INFORMS Journal on Computing (IJOC) is now available online."

header:
  teaser: "/assets/images/postimages/ijocpublication/ijoc-uav-teaser.jpg"

categories:
  - Publications
tags:
  - IJOC
  - Publication
  - Vehicle Route Planning
  - UAV Route Planning
  - Mathematical Optimization
  - Gurobi
  - R
---

 ![Screenshot of Journal Paper Page](/assets/images/postimages/coruavpublication/cor-uav.png){: .align-right}

Our latest paper that was accepted for publication in the prestigious INFORMS Journal on Computing (IJOC) is now available online at **["Unmanned Aerial Vehicle Information Collection Missions with Uncertain Characteristics".](https://pubsonline.informs.org/doi/10.1287/ijoc.2022.1245)**

We carried out this study with my colleague Michael D. Moskal II and Professor Rajan Batta from the Department of Industrial and Systems Engineering at the State University of New York at Buffalo.

If you are interested in learning more about "Route planning problem of UAVs" this paper may fit well to your interests. Specifically, we study UAV route planning problem for information collection missions performed in terrains with stochastic attributes. We developed a mathematical optimization model that is robust to the different problem types (military or civilian) and terrain properties and can be used for practical-sized missions, and showed with a simulation study that the failure rate of its optimal routes in actual missions is negligibly small.

<i class="far fa-sticky-note"></i> **Note:** This paper is also interesting in terms of the extensive and efficient usage of analytics. More specifically, we programmed the all experiments using R programming language and solve the mathematical models using the [GUROBI Optimizer 9.0.0](https://www.gurobi.com/) through [R 3.5.3](https://www.r-project.org/). All experiments were performed at the [Center for Computational Research of University at Buffalo](http://hdl.handle.net/10477/79221), on a Dell 32-core computer running Linux Centos 7.5.x with processor Intel Xeon Gold 6130 CPU, 32 x 2.10GHz and 192 GB usable RAM. We are grateful to the University at Buffalo for allowing us access to their Center for Computational Research for high performance computing resources.

We share the input data and R scripts of the military and civilian applications of our case study on GitHub to promote reproducibility and support the findings of this study. They are available within the paper and its Supplementary Information [https://pubsonline.informs.org/doi/suppl/10.1287/ijoc.2022. 1245] or are available from the IJOC GitHub software repository (https://github.com/INFORMSJoC) at [http://dx.doi.org/10.5281/zenodo.7055494.
{: .notice--info}

## Access
If you have trouble with accessing the paper, please feel free to contact me so that I can provide you with the full text.

## Abstract

We study the unmanned aerial vehicle (UAV) route planning problem for information collection missions performed in terrains with stochastic attributes. Uncertainty is associated with the availability of information, the effectiveness of the search and collection sensors the UAV carries, and the flight time required to travel between target regions in the mission terrain. Additionally, uncertainties in flight duration vary the detection threat exposed in missions performed in nonfriendly terrains. We develop a mixed integer programming model to maximize the expected information collection while limiting the risks of not completing the mission on time and of being detected and restricting the variance imposed on flight duration. The model allows multiple path alternatives between target pairs and revisits to the same target regions. Computational experiments are performed on randomly generated instances to investigate the impact of problem parameters and mission restrictions. We also develop a case study with a military and a civilian application, each of which with different specifications. In addition, we validate that the actual performance of the optimal solution of the model is close to the result reported by the solver via a simulation study. We conclude that the developed model is robust and can be used for practical-sized missions, and the failure rate of its optimal routes in actual missions is negligibly small.

## Keywords:
OR in defense, UAV route planning, Information collection, Integer programming, Stochastic programming
