---
title: What is power
tags: [getting_started]
keywords: power, Type I error, Type II error, alpha level, sample size
last_updated: September 27, 2022
summary: "Statistical power refers to the ability of a study to detect a difference of interest if it exists."
sidebar: mydoc_sidebar
permalink: mydoc_what_is_power.html
folder: mydoc
---

## Understanding statistical power

Simply put, power is the ability to distinguish the signal from the noise.  If the signal is stronger than the noise you will have higher power to determine an effect.  If the noise is stronger than the signal your power to determine an effect will be small. 

In a seroprevalence study you may be interested in determining if the seroprevalence in study area B is larger than in study area A (H0 = Sa ≥ Sb; Ha = Sa<Sb).  If you determine that the seroprevalence in B is larger when it is not that is a Type I error.  If you do not determine that the seroprevalence is larger in B when it is that is a Type II error.  Generally, in hypothesis testing we limit the Type I error by presetting the alpha level (acceptable Type I error level).  This is usually limited to 5% or alpha=0.05.  In a power analyses we are essentially trying to limit the Type II error as the Type II error is 1-Power.  

There are three main factors that influence Power: the difference you want to detect, the variability in the estimates, and the Type I error.  The variability in the estimates is directly related to the number of samples that are collected (more samples = lower variability).  Based on the difference you want to detect and the Type I error you are willing to accept, we can determine how many samples you need to collect to get the desired Power. 


## Keep in mind
1.	Best to do power calculations early 
    * Good to know if the impact you want to be able to show is feasible with samples sizes that you would be able to collect
2.	Determining the difference you are interested in is often difficult
    * Power calculations are based on what kind of difference you want to see (larger differences are easier to find than smaller ones). The power of the test will depend on the difference you are interested in.  You need to think critically about this value.
3. Power calculations are a rough guide and not an exact science
    * Power calculations are based on the assumptions you set, if reality varies from these assumptions the power calculations may be off.  Keep this in mind when setting your values and err on the side of caution.


{% include links.html %}
