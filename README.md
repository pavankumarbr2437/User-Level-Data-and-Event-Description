



#   User Level Data analysis
Dashboard Link - https://app.powerbi.com/links/ne1TOBnD7W?ctid=0abc8a22-567e-4918-b31c-0bdf83a88a27&pbi_source=linkShare



#Problem Statement
The main aim was to analyse data and KPIs including Unique Users, Total Events,and to build relationship between event data and to analyse the trends.

#Steps Carried Out-
Step1- Imported the Excel file into power bi and performed ETL process.
Step 2 - Identified KPIs like Unique users, Total Events,Engagement rate, Event popularity and event distribution.

Step 3 - Performed DAX for
1)EngagementRate = [Total Events]/[Unique Users]
2) event distribution = COUNTROWS('Event Description Mapping')
3) event popularity = COUNTROWS('Event Description Mapping')/COUNTROWS(DISTINCT('Event Description Mapping'[Description]))
4) Unique Users = DISTINCTCOUNT('User - Event Raw Dataset'[user_id])
5) Total Events = COUNTROWS('User - Event Raw Dataset')

Step 4 - Developed two dashboards Event and User level data by displaying all these KPIs. Some visuals included -
a) Event Distribution by Section
b) Event by Year
c) Total Events Over Time
d) Engagement trend.
e) Unique users over Time.

#Snapshot of Dashboard Image
![Event dashboard](https://github.com/pavankumarbr2437/User-Level-Data-and-Event-Description/assets/145674009/ab4df4ea-19a5-4518-bf7e-c60ff885a90d)
![User data dashboard](https://github.com/pavankumarbr2437/User-Level-Data-and-Event-Description/assets/145674009/14dacc6b-3de6-4f43-9591-a3318daf9e81)

#   Insights
Achieved a 4.06% increase in engagement rate between October 2022 and February 2023, despite a decline in unique users and total events.

 

