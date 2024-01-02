---
title: "Bayesian decoding of neural stimuli"
layout: post
date: 2019-01-01 00:00
tag: jekyll
image: https://sergiokopplin.github.io/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: true
projects: true
hidden: false # don't count this post in blog pagination
category: project
author: diego.arri
externalLink: false
link: false
description: "
Used many machine learning methods together with Bayesian decoding to study 
how neurons transmit information and map stimuli to responses. 
I developed a Python library that performs the optimizations needed to fit the models and 
perform the decoding.
[<a href = https://elifesciences.org/articles/80250 target=_blank>Paper</a>]
[<a href = https://github.com/diegoarri91/iclamp-glm target=_blank>Github</a>]
"
---

How do neurons encode and decode stimuli? In one of my PhD projects, I studied this question using machine 
learning applied to time series neural data. By fitting generalized linear models to the data, we can predict and 
understand how neurons map input stimuli to responses. Then by using synthetic responses I used a Bayesian framework to 
decode stimuli to explore how neurons transmit information. I developed a Python library to fit the models and performed 
the decoding, including the optimization problem. In this project, I also applied methods like linear discriminant 
analysis, information theory and methods for time series analysis. The work was published in eLife.