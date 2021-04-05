---
date: "2021-04-05T00:00:00Z"
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
url_pdf: "https://www.biorxiv.org/content/10.1101/2021.04.04.438346v1"
url_slides: ""
url_video: ""
# Here are the [Notes](https://ttuowang.github.io/causal-inference-notes/).

# Recommended textbook:

# - Paul Rosenbaum. “Design of OBservational Studies” (2010)
# - Miguel Hernan & James Robins. “Causal Inference” (2019)
# - Guido Imbens and Don Rubin. “Causal Inference for Statistics, Social, and Biomedical Sciences” (2015)

---

We propose a method for analyzing the variability in smooth, possibly nonlinear, functionals associated with a set of product production trajectories measured under different experimental conditions. The key challenge is to make meaningful inference on these parameters across different experimental conditions when only a limited number of measurements in time are collected for each treatment, and when there are only a few, or no, replicates available. For this purpose we adopt a modeling approach by representing the production trajectories in a B-spline basis, and develop a bootstrap-based inference procedure for the parameters of interest, also accounting for multiple comparisons. The methodology is applied to study two types of quantities of interest - "time to harvest" and "maximal productivity" in the context of an experiment on the production of certain recombinant proteins under laboratory conditions. We complement the findings by extensive numerical experiments that look into the effects of different types of bootstrap procedures and associated schemes for computing p-values for tests of hypotheses.
