---
title       : Developing Data Products Project
subtitle    : Hospital Statistics
author      : Anusha Vijayaraghavan
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

1. The dataset used in this analysis is taken from the sample data provided in the R programming course.
2. This data is a collection of different hospitals from different states and their metrics for a given speciality


--- .class #id


## Description

1.Based on the given metrics, the hospitals are sorted for a given speciality for different states.
2.The hospitals are ranked based on the mortality rate for a given speciality.
3. The results are stored as ranks for a particular speciality in a given state.

--- .class #id

## Description (Continued)

1. In the shinyapp, the inputs given are : state, specialty and rank.
Rank can be described in numbers, for example "1" corresponds to the best hospital or it can also be described in words like "best" and "worst".
2. The shinyapp would give the hospital name that matches the given criteria.

--- .class #id





```r
rankhospital("AL", "heart attack", 1)
```

```
## [1] "CRESTWOOD MEDICAL CENTER"
```
