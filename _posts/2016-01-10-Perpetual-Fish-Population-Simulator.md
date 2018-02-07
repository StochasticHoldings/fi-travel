---
layout: post
title: Perpetual Fish Population Simulator
---

The Peterson Estimate for population size $$\hat N$$ is a function of the fish tagged and released (**M**), the number of fish checked for tags (**C**), and the number of fish recaptured after being tagged (**R**).

                         **1**      

$$  \hat N = \frac {MC}{R}  $$

Since $$  \hat N $$ is an estimate of population, the level of effort put into bow (**M**) & (**C**) will give different estimates of $$  \hat N $$, with the most accurate estimates being much higher values of each variable.

(**M**) can be controlled by researchers, therefore the greater the investment, the greater the accuracy. See (D.S. Robin & H.A. Regeir).

(**C**) is representative of the effort put into a fishery and is something that researchers can determine through experimentation. (Basically how many people are fishing, and how easily do those people catch this fish).  Since we worked in the past with South Florida Bonefish, we will use this as an example. Prilimenary data can be used to determine (**C**), followed by a logbook program which will give us a better estimate for C.

The error associated with population estimates made by this estimation technique is calculate where:

$$ 1 -\alpha $$ is the probability that the population estimate will not differ from the true population by more than **pN**, where **p** denotes the level of accuracy.

                                        **2**

  $$1 -\alpha \leq p (-p \lt \frac {\hat N - N}{N} \lt p) $$

                                         **3**
  Substituting **1** and **2**

   $$ 1 -\alpha \leq p(\frac{MC}{(1+p)N} \lt R \lt frac{MC}{(1-p)N} ) $$

   The following is determined using a hypergeometric distribution.


   -------------------------------------------------------------------------

   The Bonefish population of South Florida is estimated using Census data (Ault et. Al) to be between
   200,000 and 500,000 fish.  So simply sampling the effort space would need to be the shaded region of (figure.2.2 ) (page 220 of DS Ropson and HA Regier)


----------------------------------------------------------------------------
#### Understanding Bonefish Movements In Their Range Using The Peterson Estimator & Monte Carlo Simulation

Researchers of South Florida Bonefish (Ault Census, Mike Larkin Dissertation, Robert Humston) have broken up the bonefishes range in South Florida into 19 zones.  A map will be provided for this page but is not here yet.  We can use simulation to simulate bonefish movements between these zones.  Therefore we would have to adjust the Peterson estimate just slightly.


** 4  **

##### Adjusted Peterson Estimate For Zones

![Adjusted Peterson Estimate For Zones](http://127.0.0.1:4000/img/Bonefish_Simulator/page1.jpg)

##### Understanding The Adjusted Peterson Estimate For Zones

![Undertanding Adjusted Peterson Estimate For Zones](http://127.0.0.1:4000/img/Bonefish_Simulator/page2.jpg)

#####  MarkovChain Monte-Carlo Simulation & Efficient Utilization Of Tagging Efforts

![MarkovChain Monte-Carlo Simulation & Efficient Utilization Of Tagging Efforts ](http://127.0.0.1:4000/img/Bonefish_Simulator/page3.jpg)
