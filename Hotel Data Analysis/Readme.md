# Hospital Management Case Study🏥

### Dashboard Link : https://github.com/Farheen-Masoom/Power-Bi-Dashboard/blob/main/Hotel%20Data%20Analysis/Hotel_Data_Analysis.pbix

## Problem Statement
1.Data Cleaning and transformation

Perform data cleaning on dim_hotels
replace “tajj” -> “taj”
remove the delimiter present in the elements of property name
remove duplicates if necessary
rename delhi->Delhi
count rows of dim_hotels 
group the data based on Mumbai, Hyderabad, Bangalore in city column then delete this step
perform additional cleaning if necessary

2.Perform data transformation in dim_rooms

3.Extract month name and week number from the year from dim_date table make column of these(using custom column feature of power query)

4.Handle null values if present (do not delete any rows)

5.Perform data modelling on the datasets that we are using(upload the screen shot)

6.Dax Calculated Columns (Note: you can use google if necessary)
Generate week-number column from date, named as wn using dax in dim_date table (upload screenshot).
Generate Dax calculated column day_type (upload screenshot). (using if and weekday function of dax measures) in dim_date table.("weekend","weekday") only values of the column.

7.Generate dax measures 

8.Data visualization:
generate slicer containing city,room_class, wn (mentioned above)
generate revenue,total bookings, occupancy %,ADR,total checkout,cancellation% KPIs as cards.
create line chart y axis→ADR and x-axis→booking platform.
create doughnut chart
revenue by category.
create stacked chart -total booking by city.
create tree map chart -fields revenue and booking platform
create table containing room_category,revenue ,total bookings,booking % by room

**Dataset Download:**
- https://docs.google.com/spreadsheets/d/19t0rnPx_EobWu7V6bw9hZd2T5BkNSN-F6yE-4s0fIaw/edit?gid=1403333110#gid=1403333110
- https://docs.google.com/spreadsheets/d/1kabCn76L4Di-T_NAMe7zWhsSa44A3ZPYaTqpwt_GhDY/edit?gid=1519030124#gid=1519030124
- https://docs.google.com/spreadsheets/d/1eDRB25NDoIkGzVI58Z7EIVqQJN6Zs1gI9L2ujQpGJZs/edit?gid=220703033#gid=220703033
- https://docs.google.com/spreadsheets/d/1rhQY8xGsjJped-qql4MDOm3vtRLsLqy1HDo8n8XEiVk/edit?gid=468823910#gid=468823910
- https://docs.google.com/spreadsheets/d/1I2lGzs_9XrYa0gk4d1htLMd6IhM69uwO9hN7I0oeRfo/edit?gid=311795675#gid=311795675



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality", "column data type" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : There should not be any blank/empty dataset , null values & duplicate data.

