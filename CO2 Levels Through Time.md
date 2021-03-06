CO2 Levels Through Time
========================================================
author: Jonathan Marin  
date: 8/27/2017
autosize: true

Introduction
========================================================

Paleoclimatologists have been studying ancient air frozen in the polar ice caps.  When Ice freezes, air bubbles are often trapped and preserved through time.  These air bubbles can then be examined and scientists have been able to measure what historic air was made up of in parts per million.  With average rising temperatures and the boom of industry and technology by man, we can see throughout history what the highest level of CO2 is and how the current century compares. The following diagram shows the rise of CO2 Levels post the Industrial Revolution era.




Data from NOAA
========================================================

The data used was collected from the NOAA website and can be found [here](https://www1.ncdc.noaa.gov/pub/data/paleo/icecore/antarctica/law/law2006.txt).  


```r
setwd("C:/Users/Marin Family/Documents/R/CO2throughTime")

climateData <- read.csv("CO2 Levels Through Time.csv")
```
```

Climate Change Plot - CO2 Parts per Million
========================================================

The following graph shows what the CO2 levels are per year in parts ber billion. 



<iframe src="demo.html" style="position:absolute;height:100%;width:100%"></iframe>


========================================================

##RShiny App

The following link will direct the user to an app that can help the user see and monitor CO2 levels. 

[ClimateChangeApp](https://jlmarin64.shinyapps.io/CO2LevelsPerYear/)
