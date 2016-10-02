---
layout: post
title: My first post
author: Peter Laurinec
published: true
status: publish
draft: false
tags: R
---
 
## Data Analysis
 
Generate random numbers:
 

    rnorm(50)
 

    ##  [1]  0.90164477 -0.52904235 -0.97554115  1.43337401  1.59342450
    ##  [6]  2.36353583 -0.21993482  0.01493647  2.84604434  0.85755949
    ## [11]  0.27791422 -1.55648839  0.43802318  0.20250319  0.19156180
    ## [16]  1.88627361  0.30820154 -0.03261732  0.43479067 -1.57080872
    ## [21] -1.29174081  1.01801441  0.82291883 -1.04906605  1.21388974
    ## [26] -1.54062925 -0.47310051  1.07816940 -0.62329591  0.72529800
    ## [31] -0.71776793 -0.29816996 -0.15710547 -0.71856132 -0.91720056
    ## [36] -2.87414665 -0.08763363 -0.67672089 -0.19421767 -0.75012408
    ## [41] -0.55554355 -0.27397664  0.84902230 -1.02492864  1.54007348
    ## [46] -0.17722916 -1.17514728 -0.44636277 -0.19739177 -0.36534734
 
## Ploting time series
 
Plot random numbers like time series:
 

    plot(ts(timeseries_1, start = 0), ylab = "", xlab = "Time")

![plot of chunk plot](/images/plot-1.png)