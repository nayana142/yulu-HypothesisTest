# yulu-HypothesisTest
## About Yulu:
Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!.Yulu has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.


## Business Problem:
 •	Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
 •	How well those variables describe the electric cycle demands  

 ## Problem Statement:
    * Relation between the dependent and independent variable
      * Bivariate:
          * Dependance of count on weathe
          * Dependance of count on season
          * Depandance of count on windspeed
          * Depandance of count in days
          * Depandance of count in month
          * Depandance of count in year
          * Count of users in each humidity level
      * Multivariate
          * Season : Count : Year
          * Season : casual : Year
          * Season : registered : Year
          * Season : temp : month
          * Season : count : month
          * Season : windspeed : month
          * workingday : count : weather
          * Season : humidity : workingday
          * Season:Humidity: Month
          * Season : registered : Year
    * Chisquare:
       * Weather is dependent on the season :Chisquare
       * workingday is dependent on the season
    * Anova :
       * No. of cycles rented is similar or different in different season
       * No. of cycles rented is similar or different in different weather
## Project Accomplishments and Process Overview
    •	Import the dataset and do usual exploratory data analysis steps like checking the structure & characteristics of the dataset
    •	Try establishing a relation between the dependent and independent variable (Dependent “Count” & Independent: Workingday, Weather, Season etc)
    •	Select an appropriate test to check whether:
    o	Working Day has effect on number of electric cycles rented
    o	No. of cycles rented similar or different in different seasons
    o	No. of cycles rented similar or different in different weather
    o	Weather is dependent on season (check between 2 predictor variable)
    •	Set up Null Hypothesis (H0)
    •	State the alternate hypothesis (H1)
    •	Check assumptions of the test (Normality, Equal Variance). You can check it using Histogram, Q-Q plot or statistical methods like levene’s test, Shapiro-wilk test (optional)
    o	Please continue doing the analysis even If some assumptions fail (levene’s test or Shapiro-wilk test) but double check using visual analysis and report wherever necessary
    •	Set a significance level (alpha)
    •	Calculate test Statistics.
    •	Decision to accept or reject null hypothesis.
    •	Inference from the analysis
