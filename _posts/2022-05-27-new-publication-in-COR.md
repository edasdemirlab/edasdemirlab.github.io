---
title: "Our New Paper in Computers & OR is Now Available Online"
layout: single
classes: wide
author_profile: true
read_time: true
comments: true
share: true
related: true
show_date: true

excerpt: "Our latest paper that was accepted for publication in the prestigious Computers & Operations Research (COR) is now available online."

header:
  teaser: "/assets/images/postimages/coruavpublication/coruav-teaser.jpg"

categories:
  - Publications
tags:
  - COR
  - Publication
  - Vehicle Route Planning
  - UAV Route Planning
  - Multi-objective
  - Optimization
  - Gurobi
  - R

---

 ![Screenshot of Journal Paper Page](/assets/images/postimages/coruavpublication/cor-uav.png){: .align-right}

Our latest paper that was accepted for publication in the prestigious Computers & Operations Research (COR) is now available online at **["UAV routing for reconnaissance mission: A multi-objective orienteering problem with time-dependent prizes and multiple connections".](https://www.sciencedirect.com/science/article/pii/S0305054822001526")**

We carried out this study with Professors Rajan Batta, Murat Koksalan and Diclehan Tezcaner Ozturk during my research visit to the Department of Industrial and Systems Engineering at the State University of New York at Buffalo.

If you are interested in learning more about "Route planning problem of UAVs" this paper may fit well to your interests. We study the UAV route planning problem in a radar-monitored environment as a multi-objective orienteering problem with time dependent prizes and multiple connections. I believe the paper has the potential to trigger important developments in the field. In addition, our approach is quite general in nature and can be adapted to problems such as inspection of wild life, search and rescue operations, crowd monitoring, border patrolling, video recording in sport games, as well as to the operations of underwater and ground vehicles.


<i class="far fa-sticky-note"></i> **Note:** This paper is also interesting in terms of the extensive and efficient usage of analytics. More specifically, we programmed the all experiments using R programming language and solve the mathematical models using the [GUROBI Optimizer 8.1.0](https://www.gurobi.com/) through [R 3.5.3](https://www.r-project.org/). All experiments were performed at the [Center for Computational Research of University at Buffalo](http://hdl.handle.net/10477/79221), on a Dell 32-core computer running Linux Centos 7.5.x with processor Intel Xeon Gold 6130 CPU, 32 x 2.10GHz and 192 GB usable RAM. We are grateful to the University at Buffalo for allowing us access to their Center for Computational Research for high performance computing resources.
{: .notice--info}

## Free Access
The publisher, Elsevier, gave me a personalized URL that provides 50 days' free access (until July 16, 2022) to anyone with the link. You are welcome to read or download. No sign up, registration or fees are required.

>Free Access Link: [UAV routing for reconnaissance mission: A multi-objective orienteering problem with time-dependent prizes and multiple connections](https://authors.elsevier.com/c/1f8jK15N8SJMjs)

After July 16, 2022 the paper will be available on [COR's web site](https://www.sciencedirect.com/science/article/pii/S0305054822001526?via%3Dihub).

If you have trouble with accessing the paper, please feel free to contact me so that I can provide you with the full text.

## Highlights

I strongly encourage you to read this paper if you are interested in:
- Routing of a UAV collecting information in a threat environment,
- An orienteering problem with time-dependent prizes and multiple connections,
- Mathematical programming, heuristic solution approaches, and computational experiments with analytical tools.
- Multi-objective optimization, and investigation of trade-offs between distance and radar detection threat
- A case study based on the terrain properties of the State of Colorado, US.


## Abstract

We address the route planning problem of an unmanned air vehicle (UAV) tasked with collecting information from a radar-monitored environment for a reconnaissance mission. The UAV takes off from a home base, visits a set of targets, and finishes its movement at a final base. Collectable information at a target depends on the time the target is visited by the UAV. There are multiple trajectory alternatives between the target pairs with different travel time and threat attributes. A route plan involves the selection of the targets to visit, the order of visit to the targets, and the trajectories to follow between the targets. Multiple routing objectives, information collection, mission duration and mission safety, are considered to present the trade-offs among the objectives to the route planner. The problem is classified as a multi-objective orienteering problem with time-dependent prizes and multiple connection options. A mixed integer programming model that can be used for small-sized problems is formulated. Larger problems are addressed with a hybrid algorithm involving heuristics and exact approaches. A case study based on a terrain in the State of Colorado is presented. Finally, some practical issues for the UAV route planning problem is discussed.

## Keywords:
Multiple objective programming, UAV routing, Orienteering, Time-dependent prizes, Mixed integer programming
