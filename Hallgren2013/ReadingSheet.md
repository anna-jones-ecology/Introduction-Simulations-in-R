# Conducting Simulation Studies in the R Programming Environment - Reading Sheet

***
[Hallgren A. K. 2013. Conducting simulation studies in the R programming environment. Tutor Quant Methods Psychol. ; 9(2): 43–60.](https://doi.org/10.20982/tqmp.09.2.p043) 

***

Hallgren (2014) describes the benefits of using simulations and provides examples of applications.

1)	Please list all the words that you do not know/concepts you do not understand in this paper (except mediation, branching, zero-inflation, ceiling effect, structural equation models, social network exponential random graph).  
    *  not 100% sure on bootstrapping but I have heard of it in phylogenies
    *  
    *  

2) In your own words, describe which steps are common to all sorts of simulations. Illustrate with simple examples rather than, or in addition to, using terms such as assumptions and parameters.    
**1)**   The set of assumptions and parameters of the dataset are laid out, for example for population dynamics simulation assumptions might include no emmigration and parameters might include death rate. 
**2)**  Generation of dataset according to these assumptions, for example population size over time
**3)**  statistical analysis of the dataset, model coeeficient estimates, fit indices and p-values are retained
**4)**  repeat steps two and three over many generated datasets to produce a distributionof the parameter estimates. 
**5)**  Steps 2-4 can be repeated for a different set of assumptions, eg re-run with emmigration included
**6)**  The distributions of parameter estimated are then analysed to answer research questions



3)	In your own words, describe the 3 types of applications for simulations covered by the author.  
**1)**   Assessing the impact of an intermediate variable on the dependant variable
**2)**  Estimation of the statistical power of a model, which means the probability of rejecting the null hypothesis when the null hypothesis is false. 
**3)** Obtaining confidence intervals via bootstrapping 

4)	Describe, with your own words and/or examples, the 4 limitations to simulations mentioned by the author.  
**1)**   real world data won't follow the assumptions of the simulation so the exact populaiton parameters remain unknown. Real world data is "dirty"
**2)**  You cant find the exact parameter values 
**3)**  high computation time
**4)** not all stat questions need simulating, you can answer many by mathematical methods. 