# US Passenger

### Dashboard Link : 
https://github.com/Farheen-Masoom/Power-Bi-Dashboard/blob/main/US%20Passenger/us_passenger.pbix

## Problem Statement
In the highly competitive travel industry, understanding passenger trends is crucial. The given dataset includes information about passenger visits to various countries, including details such as the country visited, the month of the visit, and the total number of passengers.

## Objective
The objective is to predict and visualize passenger travel trends based on various features, including the country visited, the month of visit, and the total number of passengers. 

## Dax calculation
Extract year from "Month" column.
Make "date" table having column: Date,year,month_name,Month Number, Quarter, weekday, week_number
using "Dax" .

**Dataset Download:**
https://docs.google.com/spreadsheets/d/1trbuYVO1bfHwsXCTqH1qGAg1FWSHnzYvWcW35GiPr20/edit?gid=0#gid=0

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality", "column data type" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : There should not be any blank/empty dataset , null values & duplicate data.
