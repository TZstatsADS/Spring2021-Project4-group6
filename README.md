# Project 4: Causal Inference

### [Project Description](doc/project4_desc.md)

Term: Spring 2021

+ Team #6
+ Projec title: Causal Inference Algorithms Evaluation
+ Team members
	+ Daryl Kow
	+ Peter Kwauk
	+ Yushi Pan
	+ Yuqi Xing
	+ Renyin Zhang
+ Project summary: In this project, our group was assigned to implement 3 different algorithms (Propensity Matching, Doubly Robust Estimation, and Stratification) to calculate the average effect of the treatment (ATE) for two datasets: high dimensional data and low dimensional data. For Propensity Matching algorithm, we had 3 different distance measures: Mahalanobis, propensity score, and linear propensity score. Except for the Mahalanobis method which does not require the calculation of propensity score, we used logistic regression to estimate the propensity score. At the end we compared the performance (ATE error & running time) of each algorithm.
	
**Contribution statement**: 
+ Daryl: Implemented pairing 1 and 2 for the low dimensional data and tuned the respective algorithms for the best matching method (based on ATE). Contributed to slides on pairing 1 and 2, as well as the motivations for propensity matching.
+ Peter created both of the stratification algorithms, translating the theoretical mathematics of the research document into code, including an alternate method that required extensive knowledge of dplyr and regression, presented for the team, and drew the conclusion about which algorithms were the best. 
+ Yushi: Calculated the propensity score using logistic regression, implemented Doubly Robust Estimation algorithm. Contributed to the presentation slides. Wrote the summary of readme file.
+ Yuqi: Created the Linear Propensity Score using logistic regression (pairing 5), calculated the ATE, ATE error and running time for low dimension and high dimension, participated in the every meeting and contributed to the the presentation slides. Helped to improve the report. 
+ Renyin: Created and updated summary report on the algorithms, including adding processing time for pairing 1, 2, and 5. Implemented pairing 1 and 2 for high and low dimensional data. Helped Peter with understanding the alternative method on stratification. Modified algorithm for pairing 5 and tuned it with subclassification method. 


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
