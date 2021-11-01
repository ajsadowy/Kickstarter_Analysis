# Kickstarter_Analysis
Kickstarter data analysis to find trends.
===
## Layout
Kickstarter_Challenge.xlsx  

Resources (folder)  

>Outcomes_vs_Goals.png  
>
>Theater_Outcomes_vs_Launch.png  
>

## Project Overview
### Purpose
This project's objective was to continue building and reaffirming my skill set with Microsoft Excel.
The dataset  provided contains information of performing art kickstarter projects. It contains project names, fundraising goals, pledges, deadlines, launching
 dates, etc. Using the data, I focused on analysing two perspectives: theater outcomes by launch dates and outcomes based on goals for play performances.
 ## Analysis and Challenges
 ### Analysis of Outcomes based on Launch Date
 I utilized pivot tables to set up a table to see if there was a correlation with the time of a year and the projects' outcome.
 ### Analysis of Outcomes Based on Goals
 Using the COUNTIFS() function, I set parameters to count in seperate columns the number of successful, failed, and canceled projects. I further calculated the percentages of each to the total number of projects based on their goal size.
 ## Challenges and Difficulties Encountered
 One challenge that was encountered was converting the launched date from its unix data set of time to an easier to read day month year form. I was able to accomplish this by using the formula: =(B5/86400)+DATE(1970,1,1) where B5 is the input cell. This formula was found on (https://exceljet.net/formula/convert-unix-time-stamp-to-excel-date).
 ## Results
 Two noticable trends were: the beginning summer months having the highest difference of successful projects to failed projects, and the gap between the two narrows as the year proceeds to winter with the number of successful projects decreases. This information could be useful to help future projects succeed by selecting a launching date in May or June. One should look further to see if this trend follows for all categories of performances.  
   
 For plays, there were higher successful projects with a larger project goals. Unfortunately there was only a small pool of large goal play kickstarters so this trend may not be completely accurate without a larger sample size.
