---
title       : Census Visualisation App
subtitle    : 
author      : Geoffrey Smith
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Census Data

You have this census data...


```r
counties <- readRDS("data/counties.rds")
head(counties)
```

```
##              name total.pop white black hispanic asian
## 1 alabama,autauga     54571  77.2  19.3      2.4   0.9
## 2 alabama,baldwin    182265  83.5  10.9      4.4   0.7
## 3 alabama,barbour     27457  46.8  47.8      5.1   0.4
## 4    alabama,bibb     22915  75.0  22.9      1.8   0.1
## 5  alabama,blount     57322  88.9   2.5      8.1   0.2
## 6 alabama,bullock     10914  21.9  71.0      7.1   0.2
```

--- .class #id 

## Now What?

It's not very easy to see what's going on when the data is just displayed in a table format

<div style='text-align: center;'>
    <img height='560' src='assets/img/confused.jpeg' />
</div>

--- .class #id 

## Imagine

But what if we had a way to visualise this data

<div style='text-align: center;'>
    <img height='400' src='assets/img/aha.jpeg' />
</div>

--- .class #id 

## Visualise

Introducing the Census Visualisation App

<div style='text-align: center;'>
    <img height='350' src='assets/img/app.jpg' />
</div>

Click <a href="https://geloofy.shinyapps.io/census-app">here</a> to try it now!
