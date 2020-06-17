---
layout: archive #archive
title: Reading Notes
permalink: /reading/
author_profile: true
---

# Literature on routing

## Exact Analysis


#### Susan H. Xu and Y. Quennel Zhao (1996) Dynamic Routing and Jockeying Controls in a Two-Station Queueing System. Advances in Applied Probability 28(4): 1201-1226.

This paper studies optimal routing and jockeying policies in a two-station parallel queueing system. It is assumed that jobs arrive to the system in a Poisson stream with rate $\lambda$ and are routed to one of two parallel stations. Each station has a single server and a buffer of infinite capacity. The service times are exponential with server-dependent rates, $\mu_1$ and $\mu_2$. Jockeying between stations is permitted. The jockeying cost is cij when a job in station $i$ jockeys to station $j$, $i\ne j$. There is no cost when a new job joins either station. The holding cost in station $j$ is $h_j$, $h_1\leq h_2$, per job per unit time. We characterize the structure of the dynamic routing and jockeying policies that minimize the expected total (holding plus jockeying) cost, for both discounted and long-run average cost criteria. We show that the optimal routing and jockeying controls are described by three monotonically non-decreasing functions. We study the properties of these control functions, their relationships, and their asymptotic behavior. We show that some well-known queueing control models, such as optimal routing to symmetric and asymmetric queues, preemptive or non-preemptive scheduling on homogeneous or heterogeneous servers, are special cases of our system.
  

## Heavy Traffic Analysis

#### 1.  Kelly, F.P. & Laws, C.N. 1993. Dynamic routing in open queueing networks: Brownian models, cut constraints and resource pooling+ Queueing Systems 13: 47–86.

We present an introductory review of recent work on the control of open queueing networks. We assume that customers of different types arrive at a network and pass through the system via one of several possible routes; the set of routes available to a customer depends on its type. A route through the network is an ordered set of service stations: a customer queues for service at each station on its route and then leaves the system. The two methods of control we consider are the routing of customers through the network, and the sequencing of service at the stations, and our aim is to minimize the number of customers in the system. We concentrate especially on the insights which can be obtained from heavy traffic analysis, and in particular from Harrison's Brownian network models. Our main conclusion is that in many respects dynamic routing simplifies the behaviour of networks, and that under good control policies it may well be possible to model the aggregate behaviour of a network quite straightforwardly. 


## Heuristics
#### 2. Argon, N. T., Ding, L., Glazebrook, K. D., & Ziya, S. (2009). Dynamic routing of customers with general delay costs in a multiserver queuing system. Probability in the Engineering and Informational Sciences, 23(2), 175-203.

We consider a network of parallel service stations each modeled as a single-server queue. Each station serves its own dedicated customers as well as generic customers who are routed from a central controller. We suppose that the cost incurred by a customer is an increasing function of her time spent in the system. In a significant advance on most previous work, we do not require waiting costs to be convex, still less linear. With the objective of minimizing the long-run average waiting cost, we develop two heuristic routing policies, one of which is based on dynamic programming policy improvement and the other on Lagrangian relaxation. In developing the latter policy, we show that each station is “indexable” under mild conditions for customers’ waiting costs and also prove some structural results on the admission control problem that naturally arises as a result of the Lagrangian relaxation. We then test the performance of our heuristics in an extensive numerical study and show that the Lagrangian heuristic demonstrates a strong level of performance in a range of traffic conditions. In particular, it clearly outperforms both a greedy heuristic, which is a standard proposal in complex routing problems, and a recent proposal from the heavy traffic literature.

#### 3. K. D. Glazebrook, C. Kirkbride, J. Ouenniche. (2009) Index Policies for the Admission Control and Routing of Impatient Customers to Heterogeneous Service Stations. Operations Research 57(4) pp. 975-989.

We propose a general Markovian model for the optimal control of admissions and subsequent routing of customers for service provided by a collection of heterogeneous stations. Queue-length information is available to inform all decisions. Admitted customers will abandon the system if required to wait too long for service. The optimisation goal is the maximisation of reward rate earned from service completions, net of the penalties paid whenever admission is denied, and the costs incurred upon every customer loss through impatience. We show that the system is indexable under mild conditions on model parameters and give an explicit construction of an index policy for admission control and routing founded on a proposal of Whittle for restless bandits. We are able to gain insights regarding the strength of performance of the index policy from the nature of solutions to the Lagrangian relaxation used to develop the indices. These insights are strengthened by the development of performance bounds. Although we are able to assert the optimality of the index heuristic in a range of asymptotic regimes, the performance bounds are also able to identify instances where its performance is relatively weak. Numerical studies are used to illustrate and support the theoretical analyses.



