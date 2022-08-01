
---
date: "2022-07-05T00:00:00Z"
external_link: ""
image:
  caption: time-to-harvests of different treatments
  focal_point: Smart
links:
summary: Develop a statistical framework for analyzing the variability in smooth, possibly nonlinear, functionals associated with a set of growth trajectories measured under different experimental conditions.
tags:
- regression
- bootstrap
- simultaneous testing
title: Analysis of variability of functionals of growth trajectories based on limited data
author: ["Shuting Liao", "Kantharakorn Macharoen", "Karen A. McDonald", "Somen Nandi", "Debashis Paul"]

url_code: ""
url_pdf: "https://www.mdpi.com/1422-0067/23/14/7628"
url_slides: ""
url_video: ""
# Here are the [Notes](https://ttuowang.github.io/causal-inference-notes/).

# Recommended textbook:

# - Paul Rosenbaum. “Design of OBservational Studies” (2010)
# - Miguel Hernan & James Robins. “Causal Inference” (2019)
# - Guido Imbens and Don Rubin. “Causal Inference for Statistics, Social, and Biomedical Sciences” (2015)

---

Making statistical inference on quantities defining various characteristics of a temporally measured biochemical process and analyzing its variability across different experimental conditions is a core challenge in various branches of science. This problem is particularly difficult when the amount of data that can be collected is limited in terms of both the number of replicates and the number of time points per process trajectory. We propose a method for analyzing the variability of smooth functionals of the growth or production trajectories associated with such processes across different experimental conditions. Our modeling approach is based on a spline representation of the mean trajectories. We also develop a bootstrap-based inference procedure for the parameters while accounting for possible multiple comparisons. This methodology is applied to study two types of quantities-the "time to harvest" and "maximal productivity"-in the context of an experiment on the production of recombinant proteins. We complement the findings with extensive numerical experiments comparing the effectiveness of different types of bootstrap procedures for various tests of hypotheses. These numerical experiments convincingly demonstrate that the proposed method yields reliable inference on complex characteristics of the processes even in a data-limited environment where more traditional methods for statistical inference are typically not reliable.
