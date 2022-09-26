# Matplotlib-UofT-PyberAnalysisChallenge
# PyCitySchools with Pandas - Challenge

### University of Toronto - Data Analytics Boot Camp - Module 4 - PyCitySchool

---

## Overview of the Analysis

The analysis has been conducted to illustrate the "Total Fare" during a period of time in different city types. Not only can this enable us to see total amount of fares over time, but also it will provide us with a great tool for camparing fares in different city types.

---

## Analysis Phases

  1. Import Datasets
  2. Merge two datasets
  3. Calculation of **Weekly Fares** in **Different City Types** over a **Specific Period of Time**
  4. Create the desired visaluzation

---

## Results

![](/Analysis/Pyber_Summary_DataFrame.png) 

---

![](/Analysis/PyBer_fare_summary.png) 

According to above multi-line chart and the summary DataFrame, the following insights has been extracted.
  * Considering total amount of Fare, Urban city type is ranked first, Suburban city type is ranked second, and the Rural city type is at the third place.
    * Pyber has earned nearly $40,000 in Urban areas, which is almost 10 times higher than. Rural areas.
    * The most thrived type of city is Urban area, considering total amount of Fare.
  * Total number of Rides and Drivers are also follow the pattern explained for Total Fares.
  * However, considering average Fare per Ride, Rural areas is placed at the first rank.
    * This means for every single ride in these areas, PyBer will earn more.
  * For average Fare per driver, the story is the same. Rural areas are at the first place the with average Fare over three times higher than Urban areas.
    * This is because not only is average Fare per ride, higher in these areas, but also each driver will have more rides during the considered period.
    * Despite the fact that there is a noise in the chart during the considered period, the Fare amounts are relatively constant and there were no significant upsurge or drop in the trend (except a couple of times).

---

## Summary

There are some recommendations as below.
1. In rural areas, we need more drivers. We might use some incentive in order to register more and more drivers in these areas.
2. In Urban areas, we might be offering more drivers, considering the demand. For now, we must stop registering new drivers in these areas.
3. In Urban cities, the level of Fare per ride seems very low, considering Urban driving difficulties such as traffic. We need to revise our pricing in Urban cities.
