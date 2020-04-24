# Causal inference of the policy Strategy on the epidemic outbreaks  


## Authors 

[Qingtao Cao](https://www.researchgate.net/profile/Qingtao_Cao), [Junyao Wang
](https://towardsdatascience.com)

## Abstract
The epidemic of 2019 Novel Coronavirus is spreading very fast around the world. Without the useful antivirial drugs and the vaccines to repond the cov-19, the soical distanceing is a main approach to slower the spread of covid-19 becuase this disease spreads primarily from person to person. As an authoriative policy, social-distaning is applied in many different communities. According to own situation, each community begins to employ the social-distancing policy at differnt time point and applys it with different strength. The following analysis focuses on the causal effect of the three inventions, incudling the density of the community, the policy power and the moment when the policy begin to be applied, on the peak number of the infected case. First of all, we build a SIR model based on a pyhiscal-contact based network, and then run the model with the Gillespie algorithm. The Gillespie algorithm can be also descirbed as a directed acycile graph. Based on this directed acycle graph, the causal effect of above three interventions on the peak number can be quantified by two methods. One is the tranditional mathematical analysis by solving the ordinary differential equaiton and then condtion on the equation in the peak time. The other one is the observation/data analysis. In the absence of available data, we simulates the epidemic spread in our SIR model, and then use the outcome of the simulation to check the causal effect of each intervention and build a nerual netowrk prediciton model. Our results can compare the causal effect of two different policy strategies, inculding how and when applied it. What's more, we do a conterfactual analysis with the given peak number and the moment of policy being applied: if the poplicy is appled eailer, what the change is.
