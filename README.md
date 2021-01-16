# Project-1
Hello this is the **Project 1 Challenge** homework that corresponds to the 7th unit of the _Data Analisis bootcamp course_, on this homework we were assign to form a team and do some Data Anlysis about a common subject of interest then do a presentation in class with our own conclusions.    

Some of the project/presentation requirements we have to cover are:  

-Use different sources for data collection.  
-Use Pandas to clean and format your dataset(s).  
-Create a Jupyter Notebook describing the data exploration, cleanup process and illustrating the final data analysis.  
-Use different sources for data collection.   
-Create a write-up summarizing your major findings.  
-Describe the core message or hypothesis for your project on the presentation.  
-Summarize where and how you found the data you used to answer these questions.  
-Summarize your conclusions.  


**Team:**    
-Kirstan Komajda.  
-Will Sargent.  
-Roberto Diaz Briones.  

**Project:**  
Dimensions of Quality of Life vs. Working Hours in the U.S.A.


## Dimensions of Quality of Life vs. Working Hours in the U.S.A. ##  
We want to find out what the most important components of a good life are, how they correlate with each other, and how well the U.S. has done, since 1870, at making good lives for its people. We are interested in finding correlations between the changes in annual working hours per worker and 6 other dimensions of quality of life, in the U.S., since 1870. The dimensions of quality of life which we will be examining are life expectancy, access to high-speed internet, average years of education obtained, unemployment levels. Number of recreation areas per city, and levels of alcohol and drug consumption.  

**Quality of life** is defined as the degree to which an individual is healthy, comfortable, and able to participate in everyday activities.  

**Hypothesis**  
Every dimension of quality of life will be correlated with mean working hours/worker/year, with an r^2  >.5.

**Question:** How does time spent working affect and interact with other quality of life indicators?.

### Work-Life Balance: Average Hours Spent Working (U.S.) ###

Advantages of Work-Life Balance:  

-Increased productivity.  
-Less instances of sickness and absenteeism.  
-Staff feeling valued and that their personal and/or family life is important.  
-Improvements in employee mental health and well-being.  

![ScreenShot](/wh_time_line_plot.png)

### Years of Schooling vs. Average Working Hours ###

**Question:** Is there a relationship between years of school and working hours?
**Null Hypothesis:** There is no relationship between years of schooling and working hours.

y = -133.39x + 3474.69
R-squared = 0.8592

**Results:** Reject the null hypothesis. There is a strong negative relationship between years of schooling and working hours.

![ScreenShot](/wh_edu_scatter.png)

### Chi-Square: Educational Attainment vs. Working Hours ###

**Question:** Does educational attainment impact time spent working weekends and holidays? Is there a significant difference between these groups?.  
**Null Hypothesis:** There is no significant difference in average hours spent working weekends and holidays between groups of educational attainment.  
Critical Value= 11.07
Chi-Squared = 2.48	p-value= 0.778
**Results:** Fail to reject the null hypothesis. There is no statistically significant difference between educational attainment and hours spent working weekends and holidays.  

![ScreenShot](/wh_wkdy_bar.png)


## Work-Life Balance: Life Expectancy (U.S.A.) ##
Life expectancy is the key metric for assessing population health, it captures the mortality along the entire life course. It tells us the average age of death in a population.

** Question: ** Is there a relationship between working hours and Life Expectancy?

![ScreenShot](/data/working_hours_USA.png)
![ScreenShot](/data/life_expectancy.png)
![ScreenShot](/data/life_exp_vs_work_hrs_linear_regression.png)















