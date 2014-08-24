---
title       : Car weight & MPG
subtitle    : exploration of mtcars
author      : Jim Rhorer
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Understanding wt vs mpg

The purpose of this app is to provide an interactive way to interact with the mtcars data.

The slider allows the user to set different weight maximums and see the impact on the distribution of mpg.

---

## Do your charts just sit there?


```r
hist(mtcars$mpg)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1.png) 

---&radio

## The Big Question

### Do you want to add some adventure to your mpg histogram?


1. Nope
2. Not quite
3. _Yes!!!!_
4. No way

*** .hint 

Of course you do

*** .explanation 

Of course.  Why wouldn't you?

---

## If you answered yes...

... then my app is for you.

Not only does it draw the histogram but it also allows you interact with the chart by changing the maximum of weight of the cars in the chart.

Amazing!

---
