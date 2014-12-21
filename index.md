---
title       : T Test Calculator
subtitle    : 
author      : Chris C
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## Title Slide
Welch's T-test

The purpose of this Slidify program is to provide
users with a means of calculating a Welchs Ttest.




---


## TTests
The Welch's t-test is used for uneven sample and unevan variances.

The user inputs two values (perhaps regression coefficients) and corresponding standard errors.  The Shiny app outputs the t-value.


---



## Shiny

Why Shiny?

Shiny allows for the integration of R code into a live website.  The advantage is that the R code can be run by a server and that it is easily updated without users having to download a new program.

---


## Updates

How do update the Shiny app?

One benefit of the Shiny approach is that any updates can be automatically done to the server document and made immediately available to end users.

The Cloud!

---







