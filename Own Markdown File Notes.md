---
title: "Week 4 Practical"
author: "Tiffany Wheeler"
date: "2025-10-16"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Creating some instructions

When you use a # it serves as a comment just for you. 
When you want to assign a variable then use <-
When you want to create a vector use c(). For example my_name <- c("Tiffany", "Wheeler")
If I want to name that vector then use names(my_name) <- c("First", "Last")
To create a matrix {which is used for a collection of elemnts of the same data type} 

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
