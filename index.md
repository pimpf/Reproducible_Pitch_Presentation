---
title       : Reproducible Pitch Presentation
subtitle    : Course "Developing Data Products" at Coursera
author      : Milen Angelov
job         : COO at a waterfall
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, bootstrap, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github:
  user: pimpf
  repo: Developing_Data_Products
knit        : slidify::knit2slides
--- bg:#EEE

## About the application
<i>This application tends to do a very basic demonstration of the caret package which is a set of functions that attempt to streamline the process for creating predictive models.</i>
<p>
More information about cared package could be found <a href="http://topepo.github.io/caret/index.html">here</a>
</p>

## About caret package
<p>caret has several functions that attempt to streamline the model building and evaluation process, as well as feature selection and other techniques.
One of the primary tools in the package is the train function which can be used to
- Evaluate, using resampling, the effect of model tuning parameters on performance
- Choose the ???optimal??? model across these parameters
- Estimate model performance from a training set
</p>
<p>
There are options for customizing almost every step of this process (e.g. resampling technique,
choosing the optimal parameters etc).</p>

--- 

## What is does ##

## What is missing ##

---
## ui.R ##

How layout is organized
What widgets are used
---
## server.R ##

output print
reactive values
progress
method


---
## How to use it ##

What could be done in next release
---


