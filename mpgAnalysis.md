# Differences in Miles per Gallon for Automatic and Manual Transmissions

This document explores the relationship between different variables and miles per gallon (mpg) with a focus on the differences on mpg for manual and automatic transmissions.

## **Executive Summary**

## **Loading and Preparing the Data**


## **Exploratory Data Analysis**

A box plot is used to visually explore the relationship between transmission and mpg. It seems that Manual transmission leads to a higher fuel efficiency. However, we will need to further explore the relationship using linear regression. 
![](mpgAnalysis_files/figure-html/unnamed-chunk-2-1.png) 

By visually inspecting the non factor variables, we see that Displacement (disp), Horsepower (hp), Read Axle Ratio (drat) and Weight (wt) is linearly related to Miles per Gallon (mpg). 

There seems to be interactions between 
disp and hp.
disp and wt.
hp and qsec.
drat and qsec
![](mpgAnalysis_files/figure-html/unnamed-chunk-3-1.png) 

Next, factors variables are plotted in boxplots to visually inspect if they are also related mpg. 
![](mpgAnalysis_files/figure-html/unnamed-chunk-4-1.png) ![](mpgAnalysis_files/figure-html/unnamed-chunk-4-2.png) ![](mpgAnalysis_files/figure-html/unnamed-chunk-4-3.png) ![](mpgAnalysis_files/figure-html/unnamed-chunk-4-4.png) ![](mpgAnalysis_files/figure-html/unnamed-chunk-4-5.png) 

## **Model Selection**

To facilitate selecting a model,  


## **Residuals and Diagnostics**



## **Conclusion**



### Assumptions


## **Appendix**
Definitions
v/s - 0-V Engine, 1-Straight Engine 
