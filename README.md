# Players Statistics Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Recommendations](#recommendations)
- [Data Source](#data-source)
- [tool](#tool)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Results/Findings](#resultsfindings)

  

### Project overview

---

This football data analysis project aims to analyze the performance and characteristics of football players, The dataset provides a comprehensive view of player statistics, allowing for in-depth analysis and insights into player performance and trends.



![Football Data set](https://github.com/user-attachments/assets/6bbfd9f8-08f6-46a7-875d-7312c623a4e2)




### Data Source 


Football Data:The primary dataset used for this analysis is the "Football_data.xlsx" files, containing detailed information about football data such as player statistics, jersery number, and team information.

### Tool

- Excel - Data Cleaning and Data Visualization
  - [Download here](https:microsoft.com/Excel)
  

### Data Cleaning/Preparation

The following task were carried out during these phase:
1. Data loading
2. handling missing values
3. Data cleaning and formatting
4. Data integrity  - Removing duplicates

### Exploratory Data Analysis

EDA Involved exploring the football data to answer key questions and give insights such as:

- What are Top Players Value?
- What are Total Numbers of the Players Jersey?
- What are Wages Generated by the Players Monthly?

###  Data Analysis

Incude some intresting code worked with :

 A new column Age Group was added to the data set by using if statement to  identify the age demographics of players in the dataset.

 ```
=IF(AND(E6>=16,E6<=20),"16-20",IF(AND(E6>=21,E6<=25),"21-25",IF(AND(E6>=26,E6<=30),"26-30",IF(AND(E6>=31,E6<=35),"31-35",IF(AND(E6>=36,E6<=40),"36-40",IF(AND(E6>=41,E6<=45),"41-45","46+"))))))
```

### Results/Findings 
The Analysis results are summarized as follows:

 - The Top 5 Players Value Has the sum value of the players from the lowests range to highest Real Madrid was seen to be the highest club players with the highest value.
 - The Potential Growth of the players were carried out to result to the Average overall rating, Total Value ,Total Wage.
 - The Players Foot Preferences Varies in Percentage of 77% - 23%.

### Recommendations

Based on the Analysis ,we recommend this actions:
- Team Composition based on analysis factors like age, nationality, and preferred foot should be Adjusted to achieve a balanced and competitive squad.

  
  



   
