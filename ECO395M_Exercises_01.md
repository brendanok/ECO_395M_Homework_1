## 1) Data visualization: Flights at ABIA

What is the best time of the year to fly to New York City or Los Angeles
to minimize delays? We’ll pick these two cities because they are the
biggest cities in the United States by population.

NYC Airport Destinations: JFK  
LA Airport Destinations: LAX, SNA, ONT, LGB

    ## `summarise()` has grouped output by 'dest_city'. You can override using the `.groups` argument.

![](ECO395M_Exercises_01_files/figure-markdown_github/unnamed-chunk-1-1.png)

The average total delay time for an October flight to Los Angeles is
-0.2808989!

## 2) Wrangling the Billboard Top 100

![](ECO395M_Exercises_01_files/figure-markdown_github/unnamed-chunk-2-1.png)

Popular music become increasingly diverse until the mid 70s, but drop
rapidly until the turn of the millenium. After that, the diversity of
music rises sharply through present day.

![](ECO395M_Exercises_01_files/figure-markdown_github/unnamed-chunk-3-1.png)

Elton John has the most number of ten-week hits with fifty two of them,
while most of the artists have less than forty.

## 3) Wrangling the Olympics

    ##   q95_height
    ## 1        183

    ## Selecting by sd_height

    ## # A tibble: 1 x 2
    ##   event                      sd_height
    ##   <chr>                          <dbl>
    ## 1 Rowing Women's Coxed Fours      10.9

![](ECO395M_Exercises_01_files/figure-markdown_github/unnamed-chunk-4-1.png)![](ECO395M_Exercises_01_files/figure-markdown_github/unnamed-chunk-4-2.png)

The average age of olympic swimmers spikes up in the 1910s and drops
dramatically in the 1920s and stays that way until it starts to steadily
rise in the 1970s. The trend looks similar for both female and male
swimmers but female swimmers started at a much lower average age when
they started competing. While the age gaps closed a bit, it’s mostly
always lower than the average male swimmer age.

## 4) K-nearest neighbors

    ## Warning: package 'caret' was built under R version 4.1.1

    ## Loading required package: lattice

    ## 
    ## Attaching package: 'caret'

    ## The following object is masked from 'package:purrr':
    ## 
    ##     lift

    ## 
    ## Attaching package: 'foreach'

    ## The following objects are masked from 'package:purrr':
    ## 
    ##     accumulate, when

    ## Warning: package 'rsample' was built under R version 4.1.1

# Trim: 350

    ## Warning: executing %dopar% sequentially: no parallel backend registered

![](ECO395M_Exercises_01_files/figure-markdown_github/unnamed-chunk-6-1.png)

    ## [1] 19

    ## Warning: Removed 36 rows containing missing values (geom_point).

    ## Warning: Removed 38 row(s) containing missing values (geom_path).

![](ECO395M_Exercises_01_files/figure-markdown_github/unnamed-chunk-6-2.png)

# 65

![](ECO395M_Exercises_01_files/figure-markdown_github/unnamed-chunk-7-1.png)

    ## [1] 24

![](ECO395M_Exercises_01_files/figure-markdown_github/unnamed-chunk-7-2.png)
