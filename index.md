---
title       : Pitch Presentation
subtitle    : Black Cherry Trees Characteristics
author      : Jesse van den Berg
framework   : io2012   # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
runtime     : shiny
---

## Content

1. Dataset

2. Interactive Plot

3. Thanks

---

## Dataset

The used dataset is in the datasets package in R. It provides measurements of 3 characteristics of 31 felled black cherry trees.The characteristics are:
- Girth (inch)
- Height (ft)
- Volume (ft)

---

## Example of a possible Plot


```r
library(ggplot2)
library(datasets)
qplot(Height, Volume, data=trees)
```

<img src="assets/fig/simple-plot-1.png" title="plot of chunk simple-plot" alt="plot of chunk simple-plot" style="display: block; margin: auto;" />

---

## Thank you for reviewing my app

I hope you enjoyed this. 

Please do not hesitate to give any feedback.

Thank you for your time
