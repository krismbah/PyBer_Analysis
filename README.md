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




Figure 2:

![Figure_2](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig2.png)

Without THS ninth-graders:

![Ninth_New_Results6](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig3.png)

Without THS ninth-graders:

![Ninth_Old_Results5](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig4.png)

Without THS ninth-graders:

![Ninth_New_Results6](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig5.png)

Without THS ninth-graders:

![Ninth_Old_Results5](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig6.png)

Without THS ninth-graders:

![Ninth_New_Results6](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Fig7.png)

- How is the school summary affected?
Using the school data, an index of school type was created. Metrics regarding total student count, total school budget, per capita spending, average test scores, passing scores for math and reading, number of students passing math and reading by school, percentage of students passing math and reading scores by school, total students that passed math and reading by school and their percentages. The aforementioned metrics were then compiled into a new dataframe called "per_school_summary_df" with the following format to generate the output below:
![School_Results2](https://raw.githubusercontent.com/krismbah/PyBer_Analysis/main/analysis/Challenge_fare_summary.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the ninth graders' improved average math and reading scores. However, it lowered the percentage of students passing math, reading, and both subjects overall. THS didn't change from its number two ranking. Which indicates that the ninth graders' reading and math scores were indeed negligible. 

With THS ninth-graders:

![THS_Old_Results3](https://raw.githubusercontent.com/krismbah/School_District_Analysis/main/Results3.jpg)

Without THS ninth-graders:

![THS_New_Results4](https://raw.githubusercontent.com/krismbah/School_District_Analysis/main/Results4.jpg)

- How does replacing the ninth-grade scores affect the following:

    -Math and reading scores by grade:
     Replacing the ninth-grade scores didn't affect the math and reading scores of any other grade at THS.
    
    -Scores by school spending:
     Due to rounding, I am not certain that replacing the ninth-grade scores didn't affect math and reading scores by school spending. But it appears that way.
    
    -Scores by school size:
     Due to rounding, I am not certain that replacing the ninth-grade scores didn't affect math and reading scores by school size. But it appears that way.

    -Scores by school type:
     Replacing the ninth-grade scores improved the average reading score for "Charter" school types. However, the average math score was lowered and passing percentages were also lowered across the board.

With THS ninth-graders:

![Ninth_Old_Results5](https://raw.githubusercontent.com/krismbah/School_District_Analysis/main/Results5.jpg)

Without THS ninth-graders:

![Ninth_New_Results6](https://raw.githubusercontent.com/krismbah/School_District_Analysis/main/Results6.jpg)

## Summary

To summarize, the following changes to the school district analysis were made after ninth-grade reading and math scores from Thomas High School were omitted:

1. Reading and math scores were improved at THS.
2. The percentage of students passing math, reading, and both subjects overall declined.
3. Average reading scores for Charter schools improved.
4. Average math scores and passing percentages for math, reading, and overall declined for Charter schools.
