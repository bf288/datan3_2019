Class 2
================
Ben Ford
24/01/19

Enter data
----------

Let's create a data frame with 5 observations and 2 variables

``` r
Data <- data.frame(x=c(1:4, -5) , y=5:1)
```

Calculate correlation
---------------------

``` r
cor(Data$x, Data$y)
```

    ## [1] 0.4472136

R Markdown is key because if you are working with a big piece of data which changes all the time, changes above does not have to be changed manually because it would be done by running R Markdown.
