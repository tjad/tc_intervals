---
title       : Nature of confidence intervals
subtitle    : A place to play and understand confidence intervals
author      : Tjad I Clark
job         : Software Engineer
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## About

Welcome to the tool that will instill confidence in your understanding about confidence intervals!

Lack the confidence in your distributions? Never fear!

We have knit together a shiny application allowing one to play around with the concept of confidence intervals by means of entering the required values
in order to calculate such an interval.

We guarantee that you will obtain a better understanding of confidence intervals by exposing yourself to our application.

--- .class #id 

## Introduction

You're a brilliant minded data scientist, making great assumptions to start you off on the right foot with regards to your data distribution, however, you may get flashbacks to the day you sat in math class explaining to the teacher how you just "knew" your answer, it's not good enough and you will be faced with the problem of having to prove your statement "I'm 100% confident", or rather 95% confident, about where the data lie within your distribution. But wait.. What does that even mean?

Enter the confidence interval, your most valuable tool for backing up your statement of confidence to anyone.

---

## Sample

With our application you are able to play around with  various variables in order to generate a normal distribution as follows. Note that the distribution contains two red lines portraying your confidence interval.

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

---

## Variables

The confidence interval is based on a number of variables within your distribution and can vary between distribution families. We apply confidence intervals to the normal distribution as it tends to serve most useful in that any distribution with a well defined mean pertains to the central limit theorem forming a normal distribution after enough repititions of the distribution.

**Mean**: This is the most central point within your distribution and is used as an estimator from which to base your alternative data points around.

**Standard deviation**: Is a measure of variability within your distribution - this is the reason you require a confidence interval.

**Confidence**: A measure of confidence you would like to have that a particular data estimate (in our case the mean) will fall within the calculated interval of your distribution - i.e the confidence interval.

Get started in understanding the interactions between these variables right away by using our shiny app now!
[https://tjad.shinyapps.io/shiny_app/](https://tjad.shinyapps.io/shiny_app/)
