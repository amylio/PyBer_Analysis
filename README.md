# PyBer_Analysis
Analysis using Python scripts, Pandas Library, Jupyter Notebook and Matplotlib

## Overview of PyBer Analysis

The purpose of this project is to provide an analysis regarding the relationship between types of cities and the number of drivers/riders, total fares by driver and the total number of rides that occurred between January 2019 to April 2019. The analysis will help Pyber understand areas of opportunity in which ride-share access can be improved and determine affordability in underserved neighborhoods. The results will be presented using several types of visual aids in order to quickly summarize the findings for the CEO to review. 

In order to complete this request and aggregate the data, Pandas Library, Jupyter notebook  and matplotlibs was used to read the raw data, create and merge dataset, perform calculations and plot the results into different types of visualizations such as, scatter plot graphs, pie charts and fivethiryeight graphs.

The data was provide in two .csv files at the [city](https://github.com/amylio/PyBer_Analysis/blob/main/Resources/city_data.csv) and [rider](https://github.com/amylio/PyBer_Analysis/blob/main/Resources/ride_data.csv) level. The two datasets were then merged to combine the information into one data source.

## The Results

In reviewing the data for ride-share activities that occurred in a 4-month period (January 2019-April 2019), Urban neighborhoods represented 63% of the Total Fare ($39.9K vs. $63.5K) with the highest number of rides at 1,523 out of 2,218 total and the average fare at $26.17. Rides in Rural neighborhoods represented the highest average per ride at $37.31 compared to the Urban neighborhoods which represented the lowest average.  

![summary](https://github.com/amylio/PyBer_Analysis/blob/main/MOD5%20Challenge%20Submission/analysis/Jan-April19_Summary.png)

![piechart](https://github.com/amylio/PyBer_Analysis/blob/main/MOD5%20Challenge%20Submission/analysis/Fig5.png)
![Total Fares](https://github.com/amylio/PyBer_Analysis/blob/main/MOD5%20Challenge%20Submission/analysis/PyBer_fare_summary.png)

This can be interpreted in two ways:

* Riders in Urban neighborhoods rely on ride-shares more than any other neighborhood type, therefore the average fare can be lower due to need, the distance traveled and/or the availability of drivers in the area.
* Riders in Rural neighborhoods are paying more due to the lack of availability of drivers in their area. This can cause surge pricing and make ride-share less desirable.

![scatter plot](https://github.com/amylio/PyBer_Analysis/blob/main/MOD5%20Challenge%20Submission/analysis/Fig1.png)

The circle size in the chart above correlates with the number of drivers per city which shows a higher concentration in Urban neighborhoods compared to the other neighborhood types. Overall, of the number of drivers by city type, only 2.6% were in Rural neighborhoods compared to 80.9% in Urban neighborhoods. 

![Total Driver](https://github.com/amylio/PyBer_Analysis/blob/main/MOD5%20Challenge%20Submission/analysis/Fig7.png)

## Summary and recommendation

In summary, the majority of ride-share activities occur in Urban neighborhoods. This could be due to necessity, availability of drivers, and/or cost. In order to develop additional business in the other neighborhood types, such as Suburban and Rural areas, the recommendations are:

* Increase the number of drivers in these areas to make the service more accessible.
* Lower the cost as an initial offering to make ride-share services more desirable. This can be accomplished by providing coupons or discount codes for the first ride or a set number of rides.
* Implement an incentive based reward structure to assist in driver recruitment to support the possible demand.
