Personal Project: Real Time end to end Databricks using Pyspark

Domain: APP

Business Scenario
-------------------------------------
Product Data analysis

We have Google PlayStore dataset containing information of different apps installed rating and versions and other details and we are going to do analysis based on the data we have

Challenges facing:
-------------------------------------------------------------
 1. Data must have duplicate values
 2. Data must have blank value
 3. Data must have null value
 4. Schema might be effected
 5. Value should be clear

KPI: we can consider this possible analysis
-----------------------------------------------------------
 Clean the data
 -remove null value
 -provide proper schema based on column value
 -remove duplicate value
 -provide proper value to data
 
 Transform the data using business use cases
 
 Later we can load in Tableau for visulaization/or we can use databrics visualization

Business queries:
-------------------------------------------------------------
  1. Find out TOP 10 reviews given to the apps
  2. Find Top 10 Installed apps by user
  3. App count according to Type(Free/Paid)
  4. Show App list distribution according to Category
  5. Category wise distribution of installed app
  6. Top Paid App
  7. Top Paid rated apps

Technical contents:
----------------------------------------------
Tools: Databrics(community edition)
we are using Pyspark for analysing the data

Data: Csv format containing 10000+ records uncleaned data





