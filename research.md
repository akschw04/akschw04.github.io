---
layout: home
title: Research
permalink: /research/
slug: research
---

# Project 1: Evaluating Climate Emulation: Unit Testing of Simple Climate Models

Simple climate models (SCMs) are numerical representations of the Earth’s gas cycles and climate system. 
SCMs are easy to use and computationally inexpensive, making them an ideal tool in both scientific and decision-making contexts 
(e.g., complex climate model emulation; parameter estimation experiments; climate metric calculations; and probabilistic analyses). 
Despite their prolific use, the fundamental responses of SCMs are often not directly characterized. In this study, we use unit tests of 
three chemical species (CO2, CH4, and BC) to understand the fundamental gas cycle and climate system responses of several SCMs 
(Hector v2.0, MAGICC 5.3, MAGICC 6.0, FAIR v1.0, and AR5-IR). We find that while idealized SCMs are widely used, they fail to capture 
important global mean climate response features, which can produce biased temperature results. Comprehensive SCMs, which have non-linear 
forcing and physically-based carbon cycle representations, show improved responses compared to idealized SCMs. Even some comprehensive SCMs 
fail to capture response timescales of more complex models under BC or CO2 forcing perturbations. These results suggest where improvements
should be made to SCMs. Further, we provide a set of fundamental tests that we recommend as a standard validation suite for any SCM. 
Unit tests allow users to understand differences in model responses and the impact of model selection on results.


# Project 2: Characterization of Model Variability in CMIP5

Contributions from both unforced variability (e.g., ocean-atmosphere interactions) and external forcing (
e.g., anthropogenic greenhouse gas emissions, volcanic activity, variations in solar intensity) drive changes in Earth’s 
global mean surface temperature. Understanding the relative contributions from these different components is of great 
interest to the scientific community (e.g., detection and attribution studies, time of emergence estimates). Though many 
studies draw conclusions using estimates of, or assumptions about, unforced variability using multi-model ensembles, a 
robust characterization of model-specific unforced model variability has not been conducted. We fill this gap by developing 
a methodology to create model-specific unforced noise envelopes using complex model output from the Coupled Model 
Intercomparison Project (CMIP5) experiments. From this, we can determine how realistic complex model variability is 
compared to observations. We compare CMIP5 model results from the past1000 and PiControl experiments with two historical 
observational datasets (GISTEMP, HadCRUT4) and paleoclimate reconstructions from PAGES2k. We first examine variability in 
those CMIP5 models with sufficient data (e.g., published past1000 output and long PiControl runs) and apply our methodology 
to extrapolate information for the majority of models with less available data. We use power spectra of temperature-time 
series to compare variability across all time scales. Preliminary results suggest that observations have more variability 
than the suite of CMIP5 models investigated. Additionally, we investigate model variability at the regional level, using 
the sub-global regions defined by PAGES 2k. Our approach allows for a more robust assessment of complex model variability 
at time periods and regional levels important to human systems. 


# Project 3: Changes in Climate Sensitivity over Time

The time scales of climate system responses to anthropogenic emissions vary
depending on the chemical species emitted. Though carbon dioxide(CO2) emissions
primarily drive anthropogenic climate change, emissions of various other radiative
forcing agents, including short-lived climate forcers (SLCFs), also contribute signifcantly
to Earth's altered radiative budget. Much of the literature focuses on long-term
climate responses emphasizing analysis with equilibrium climate sensitivity (ECS)
or transient climate sensitivity (TCR). There is limited literature exploring shortterm
climate change responses occurring in a 20-30 year time horizon. To address this gap, 
we seek to clarify climate dynamics on decadal time scales with the
ultimate goal of understanding the implications of near-term emission reductions
on climate. Using observations and coupled model results from CMIP5, we analyze
the range of temperature response over time, with specific attention to the 20-30
year time sequence. Similarly, we also explore sub-global temperature responses
at a hemispheric-scale. We find that the range of responses of land/ocean varied
less than the range of hemispheric responses. Our results are a first step of better
quantifying the short-term climate responses to change in SLCFs.
