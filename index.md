---
title       : Developing Data Products - Final Assignment
subtitle    : Introduction to the Death Predictor
author      : Sekoul K
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Slide 2: Why a Death Predictor?

In a world where people have to deal with more and more distractions, it is also more important than ever to realize that life is short. An application that tells you the number of days you likely have left to live reminds you of the urgency of life and nudges you to take advantage of each day to the fullest.

On the next page, we'll take you through an example of how it works, based on a 32 year old male.

--- .class #id 

## Slide 3: How does it work?

Quite simple:


1. You enter your gender
2. You enter your age
3. You press 'Submit'
4. You look at the output on the right panel


The output will tell you how many days you have left to live, based on average life expectancy in the USA split by gender.

Example: 32 year old male


```r
daysLeft <- (76.2-32)*365
print(daysLeft)
```

```
## [1] 16133
```


--- .class #id 

## Slide 4: Next Steps

The calculation made in order to derive the output is quite simple. As a next step in this application, it would be great to add extra functionalities, such as acturial tables which can tell you how much you have left to live based on many additional factors.

--- .class #id 

## Slide 5: Conclusion

As Mark Twain once said:

<i>"Twenty years from now you will be more disappointed by the things that you didn't do than by the ones you did so. So throw off the bowlines. Sail away from the safe harbor. Catch the trade winds in your sails. Explore. Dream. Discover."</i>


<b>Thank you very much for your time!</b>

