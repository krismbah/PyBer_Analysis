# PyBer_Analysis

## Overview of the PyBer Analysis

The purpose of this analysis is to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize. In order to do so, the following metrics/tasks need to be completed: 

1. The total number of rides for each city type is retrieved.
2. The total number of drivers for each city type is retrieved.
3. The sum of the fares for each city type is retrieved.
4. The average fare per ride for each city type is calculated.
5. The average fare per driver for each city type is calculated.
6. A PyBer summary DataFrame is created.
7. The PyBer summary DataFrame is formatted as shown in the example.
8. A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
9. A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
10. A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28.
11. A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
12. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.

## Results

- Describe the differences in ride-sharing data among the different city types.
Using a scatter plot, we're able to see what appears to be a negative linear relationship between "Average Fare" and "Total Numbers of Rides" for the entire dataset. As the price of fares decline, total number of rides increase seen in Figure 1. The frequency of rides appears to be most concentrated in Urban cities and least in Rural. As such, Rural cities present the highest Average Fares and Urban cities the lowest:

Figure 1:

![Figure_1](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig1.png)

In 2019, Urban cities accounted for the the highest Number of Rides and Rural cities the lowest seen here in Figure 2:

Figure 2:

![Figure_2](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig2.png)

Rural cities accounted for the widest range of Fares. However, Urban cities were most economic with the lowest accounted Fares seen in Figure 3:

Figure 3:

![Figure_3](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig3.png)

Urban cities exhibited the largest Number of Drivers (Figure 4). Which may attribute to its market ability to keep Fares lower than Suburban and Rural cities.

Figure 4:

![Figure_4](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig4.png)

Urban cities accumulated 62.7 percent of the Total Fares by City Type. Rural cities made up only 6.8 percent (Figure 5):

Figure 5:

![Figure_5](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig5.png)

In regard to Total Rides by City Type, Urban cities accounted for 68.4 percent of total rides, Suburban cities 26.3 percent, and Rural cities 5.3 percent (Figure 6):

Figure 6:

![Figure_6](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig6.png)

Figure 7 displays how Urban cities dominated the market supply of Drivers:

Figure 7:

![Figure_7](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig7.png)

- How is the school summary affected?
Using the school data, an index of school type was created. Metrics regarding total student count, total school budget, per capita spending, average test scores, passing scores for math and reading, number of students passing math and reading by school, percentage of students passing math and reading scores by school, total students that passed math and reading by school and their percentages. The aforementioned metrics were then compiled into a new dataframe called "per_school_summary_df" with the following format to generate the output below:

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the ninth graders' improved average math and reading scores. However, it lowered the percentage of students passing math, reading, and both subjects overall. THS didn't cha

## Summary

To summarize, data from for the first quarter of 2019. The following observations were made:

1. Total Fares remained relatively flat across all three city types.
2. Total Fares appear to have the highest growth in Suburban cities.
3. Urban cities collected the highest Total Fares of all the city types.
4. Rural cities collected the lowest Total Fares of all the city types.

![Summary_Chart](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Challenge_fare_summary.png)
