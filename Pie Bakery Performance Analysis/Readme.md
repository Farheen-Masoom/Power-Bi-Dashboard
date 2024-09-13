# Pie Bakery Performance Analysis

### Dashboard Link : 
https://github.com/Farheen-Masoom/Power-Bi-Dashboard/blob/main/Pie%20Bakery%20Performance%20Analysis/Pie%20Bakery%20Performance%20Analysis.pbix
## Problem Statement
In the Bakery industry, optimizing operations and understanding revenue trends is crucial for sustained success. The dataset include different information such as order types, organic status, pie flavors, pie types, and a fact table capturing various transaction details. The challenge is to extract valuable insights, and construct a model that enhances decision-making.

**Objective**

The objective is to analyze and visualize revenue trends based on order types, organic status, pie flavors, and pie types. Key tasks include creating a DAX-based calendar table, implementing DAX measures, performing data modeling, and creating visualizations for effective insights.

**you are provided with the dataset mentioned below:**

- Dim_OrderTypes
- Dim_Organic
- Dim_Pieflavor
- Dim_PieTypes
- FactTable

**DAX Calculation**

- Create calendar table using DAX, column should be Date, year, month, month num, quarter, weekdays, week num.
- Create year DAX.
- Create measures mentioned int the screenshot and upload screenshot of all the measures.
- Perform data modelling 
**Data visualization**

- Create stacked area chart to show cumulative revenue over date
- Create column chart to show total revenue by quarters
- Create ribbon chart to show total revenue by weekday
- Create slicer for pre-order/in-store purchase
- Create table in dashboard having columns- slice or whole price, order means, total orders, total revenue.
- Create KPIs as total transaction ,total orders, total revenue, average revenue, last transaction date,2020 revenue ,2021 revenue

**Dataset Download:**
https://docs.google.com/spreadsheets/d/1st-2NIjOHxgEjws_SHT2rcfFb5Y2gGjlqugh8zGpB78/edit?gid=1879322001#gid=1879322001



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality", "column data type" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : There should not be any blank/empty dataset , null values & duplicate data.

