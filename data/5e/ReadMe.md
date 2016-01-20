# Data for the 5th Edition #

The data in this directory is used in the examples in this project and referenced directly by URL.  

The original data was obtained from the student companion website for the text "Applied Statistics and Probability for Engineers," 5th Edition by Douglas C. Montgomery and George C. Runger.  March 2010.

The data has been converted to CSV format and a number of errors were fixed.

Read data directly from R with the following code (nrow should return 120 rows):
``` R
ch06 <- read.csv("http://raw.github.com/MiddelkoopT/Stats-2016-Spring/master/data/5e/ch06.csv",header=TRUE)
nrow(ch06)
```
