---
title: "Lesson 16: Functions Part 2 and Factors in R"
output: 
  html_document:
    keep_md: yes 
    toc: true
---
  


<br>

## Readings

<br>

#### Required: 

* [Chapters 18-21: Writing your own functions](https://stat545.com/functions-part1.html) in Jenny Bryan's STAT545 notes

* [Chapter 10: Be the boss of your factors](https://stat545.com/factors-boss.html) in Jenny Bryan's STAT545 notes


<br>

#### Other resources:

* Review the assignment for last class: [Chapter 19](https://r4ds.had.co.nz/functions.html) in R for Data Science by Hadley Wickham & Garrett Grolemund

* [Chapter 15](https://r4ds.had.co.nz/factors.html) in R for Data Science by Hadley Wickham & Garrett Grolemund

<br>

## Announcements
* The final homework is due tonight

* Wednesday is our last class - we're looking forward to your presentations. To make sure we hear from everybody, we'll have to stick to a strict 1.5 min presentation per participant. Please get concrete and show us some examples of the types of data you work with or the types of computational/analytical challenges you're confronted with in your work

* If you can't give a live presentation, please upload your video on [Canvas through this link](https://canvas.cornell.edu/courses/21578/assignments/174563) by this Wednesday (Nov 11) at 10pm

<br>

## Today's learning objectives
Today, we will first practice writing a few more functions and then we'll discuss how factors work in R.

By the end of today's class, you should be able to:

* Write a simple function to automate a task
* Describe key features of factor variables in R
* Manipulate factor levels to improve plots of categorical data

<br>
<br>

## Getting set up
We will continue working with the gapminder dataset, so let's first load that back in, along with the tidyverse.


```r
library(tidyverse)
library(gapminder)  #install.packages("gapminder")

# For being able to compare plots side by side, I'm also going to use the gridExtra package today
library(gridExtra)  #install.packages("gridExtra")
```

<br>
<br>


## Quick recap on writing functions

Last time, we made a function that would save a plot of how a variable of choice changed over time for a specific country in the `gapminder` dataset. Today we'll quickly go over how we use a similar structure to write a function for computing numeric output. We'll do this with Jenny Bryan's example and calculating interquantile range in the gapminder data [here](https://stat545.com/functions-part1.html). We won't have time to cover all the details she illustrates, so if you're interested in learning more, I highly recommend working through the rest of her examples in her chapters 18-21 on your own.

<br>
<br>

## Better plots with factor level manipulation 

We'll go over [Jenny Bryan's illustration](https://stat545.com/factors-boss.html) of how a few powerful functions from the `forcats` package can significantly improve our handling of factor variables and visualization of data with categorical variables.

<br>
<br>

## THE END
This is all we had time to cover in this course. In our final class, we're looking forward to hearing all of your ideas for applying the course material in practice, and we'll go over helpful resources for learning more.
