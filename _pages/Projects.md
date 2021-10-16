---
permalink: /Projects/
---

Here are the course projects I have undertaken during my PhD studies.

# 1. A Review of EM algorithm for Missing Data
- Course: Missing Data
- Date: 2020/04 - 2020/05

Expectation-Maximization algorithm (EM) is a numerical approximation method that has mainly been used to iteratively find the maximum likelihood estimation (MLE) of the parameter (Dempster et al., 1977). The iteration of EM begins with the execution of the Expectation step (E-step), followed by the Maximization step (M-step). The iteration continues until convergence is attained. In missing data problems, the E-step serves to find the integral of the expected full likelihood conditional on observed data under the Missing at Random (MAR) assumption. Naturally, the integral of the E-step cannot be carried out analytically. To resolve this issue, Monte Carlo EM (Wei and Tanner, 1990) and Stochastic Approximation of EM (Delyon et al. 1999), which employ simulation strategies via Markov Chain Monte Carlo methods, are proposed. In this report, we briefly review the histories and the algorithms of EM, MCEM, and SAEM.  

<em>Keywords: Expectation-Maximization Algorithm, MCEM, SAEM <em>




---
# 2. Developed R package entitled MixPoiRayExp: An Expectation-Maximization Algorithm for Finite Mixture Models
- Course: Computational Statistics
- Date: 2020/10 - 2020/12

Finite mixture models are frequently seen in real-world data applications.  To identify appropriate mixture models, we need to isolate the true cluster of the data, tackling the density estimation.  The EM algorithm is commonly used to obtain the parameter estimates of the mixture model.  Most of the published R packages, such as mixture, mclust, and EMCluster, were developed primarily for handling mixture Gaussian cases.  For cases outside the scope of mixture Gaussian, the relevant R packages are quite limited.  To cope with this problem, we develop a new R packageMixPoiRayExpin this project.MixPoiRayExpcan provides the results of the point estimation with its precision in mixture Pois-son, mixture exponential, and mixture Rayleigh.  To help users obtain reliable results, two additional functions, which provide suggestions of the number of mixture components and initialization strategies for the EM algorithm, are also included inMixPoiRayExp.

<em> Keywords:  Finite Mixture Model, EM, Mixture Poisson, Mixture exponential, Mixture Rayleigh <em>

