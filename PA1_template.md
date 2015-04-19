---
title: "ReproducibleResearch_PeerAssessment1"
author: "Motaz El Saban"
date: "Saturday, April 18, 2015"
output: html_document
---?

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


Loading and preprocessing the data


```r
setwd("C:\\Users\\motazel\\OneDrive\\Documents\\Courses\\DataScienceJHUCoursera\\ReproducibleResearch\\repdata_data_activity")
activityData = read.csv("activity.csv")
```


What is mean total number of steps taken per day?





You can also embed plots, for example:


```r
xd <- plot(activityData[,1])
```

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3-1.png) 

```r
print(xd, type = "md")
```

```
## NULL
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.















---
title: "Reproducible Research: Peer Assessment 1"
output: 
  html_document:
    keep_md: true
---


## Loading and preprocessing the data



## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?

