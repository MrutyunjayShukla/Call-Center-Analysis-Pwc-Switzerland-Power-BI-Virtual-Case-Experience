# Call Center Analysis Pwc Switzerland Power BI :  Task 1
Call Center Analysis | Pwc Switzerland Power BI Task 1



## Table of Content
- Problem Statement
- Importing Data
- Data Preparation
- Data Modelling
- DAX
- Data Visualization
- Insights

## Problem Statement
- **Problem** The Manager at Phonenow is looking for insights in to the Call Center DataSet.
- **Objective** To Create a Dashboard in Power BI for Call Center mannager the reflects all relevant KPI'S:
     - Agent Performance 
     - Customer Satisfaction
     - Exploratory Data Analysis
  
- **Possible KPI'S** 
     - Overall calls answered and  resolved
     - Calls sorted by topic
     - Calls per Month
     - Agent Performance 
     - Average Talktime
     - Average Satisfaction
     - Speed of Calls
     - Calls Answered by Avg. Talk Duration in Min.
  
## Importing Data
The Dataset was provided by PWC Switzerland.

## Data Preparation
Dataset was loaded into Power BI , Data was tranformed and loaded in Power Query editor.
- Validation of each coloumn Data Type's
- Removing Unnecessary Row's and Column's

## Data Modelling 
After the dataset was cleaned and transformed, The Data is ready for Modelling.

## DAX
- **Measures used**:
     - % of Incident Resolved = [Resolved_Incident]/[Calls Answered]
     - Avg Talktime in Minutes = FORMAT(AVERAGE(Sheet1[Text After Delimiter]),"HH:MM:SS")
     - Calls Abondend = CALCULATE(COUNTROWS(Sheet1),Sheet1[Answered (Y/N)] = "N")
     - Calls Answered = CALCULATE(COUNTROWS(Sheet1),Sheet1[Answered (Y/N)] = "Y")
     - Resolved_Incident = CALCULATE(COUNTROWS(Sheet1),Sheet1[Resolved]="Y")

## Data Visualization 

## Visuals Used
- 2 Donut Chart's : Overall Calls Answered and Resolved 
- 3 Slicers's : Date, Topica and Agent
- 2 Cards's : Speed of Calls and Average Talktime
- 1 Guage : Average Satisfaction
- 1 Statcked column Chart : Calls per Month
- Line Chart : Calls Answered by Avg. Talk Duration in Min
- Table : Agent statistics

## Dash Board
Visualization from Call Center Trends

![Call Center Trends](https://github.com/MrutyunjayShukla/Call-Center-Analysis-Pwc-Switzerland-Power-BI-Virtual-Case-Experience/assets/89764972/9536c6b6-80a3-4bff-ac3a-fe6aaf6fd0f0)

## Insights
- The average satisfaction rating of Martha is the highest
- The average speed of answer by Joe is the highest
- The % of incident resolved by Greg is the highest
- The count of calls in January is more as compared to other 
- Most Calls are related to streaming 

     
