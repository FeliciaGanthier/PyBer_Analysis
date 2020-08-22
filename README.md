# PyBer_Analysis

##**Overview of Project**

As a data analyst for Pyber, a Python based ride-sharing app company valued at $2.3B, I was assigned to perform an exploratory analysis on data for the time period between January 2019 - May 2019 and create several types of visualizations showcasing the relationship between the type of city, number of drivers, number of riders and fares. This information will help our CEO make decisions abut where resources and support are needed. 

Using Jupyter Notebook and Pandas to read and inspect raw data from large CSV files, merge datasets, perform calculations and create data series and data frames, I also used Matplotlib to produce publication-quality figures to tell a story from the data in a way that is informative and engaging to all stakeholders. 

A Git Hub repository was created for the ride-sharing l analysis so my manager, Omar and our CEO, V. Isualize, can review the most recent work.

*Purpose of Analysis*

The analysis will help PyBer improve access to ride-sharing services and determine affordability in underserved neighborhoods.  

###**Results**

At Omar’s suggestion, I added statistical analysis because it will demonstrate the relevance of the data, especially the numbers of riders by city type. I also calculated summary stats for average fares by city type to determine which city types are generating the most revenue. This will help the CEO and other stakeholders make decisions about which types of cities need more driver support. 

![Deliverable 1](https://github.com/FeliciaGanthier/PyBer_Analysis/blob/master/Analysis/Deliverable%201.png)

*Key Takeaways*

•	Urban cities have the most rides and drivers, followed by suburban cities and rural cities, respectively. 

•	While the urban city fares total is more than the suburban and rural city combined total, the average fare per ride and driver is the lowest for the group. 

•	Rural cities average fare per driver is almost equal to the suburban and urban combined averages. 

A line chart was used to easily highlight which months were more profitable for each city type. Each city type had an uptick in late February. Urban and rural cities follow a similar pattern during the period, except in March where the urban cities have drops in fares roughly every other week and the rural cities remain flat.  Suburban cities drop steeply after the February peak and remain relatively flat until April where there is another dip followed by a sharp rise that appears it is on track to surpass February fares at the end of the month. 

![Deliverable 2](https://github.com/FeliciaGanthier/PyBer_Analysis/blob/master/Analysis/Deliverable2.png)

####**Recommendations Summary**

Based on the results, the suburban cities offer the best opportunity for increased revenue and I recommend the following to address disparities among the city types:

•	Increase the number of suburban drivers by reassigning rural drivers in mid-February and mid-April

•	Reassign urban drivers to suburban cities in mid-April 

•	To support the urban ride increase in March, reassign suburban drivers to urban cities. 

*Note: Additional analysis is needed to determine the recommended number of drivers for each reassignment.*

PyBer can afford to take this calculated risk reassigning urban drivers because as mentioned in the results section, the urban city fares total is more than the suburban and rural city combined total - in fact, urban fares exceed them by $10K.

The proposed reassignments will increase the average fares for suburban and urban rides during the period and while the average fare per driver will dip, the shortfall can be made up because there will be more rides. 

