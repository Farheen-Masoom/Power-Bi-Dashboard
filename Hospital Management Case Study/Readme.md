# Hospital Management Case Study🏥

### Dashboard Link :https://github.com/Farheen-Masoom/Power-Bi-Dashboard/blob/main/Hospital%20Management%20Case%20Study/Hospital%20Management%20Case%20Study%F0%9F%8F%A5.pbix

## Problem Statement

- 🎯 Objective:
  Analyze the hospital management data to derive insights and validate hypotheses about patient care and resource management. Use  MySQL for data storing and cleaning before performing analysis and creating visualizations in Power BI.
  
- 🔬 Hypotheses and Questions: For each hypothesis provided, there is a corresponding question that you need to answer using the data. create visualizations in Power BI that address these questions and validate the hypotheses.  
Q1.
Hypothesis: Efficient appointment management can improve patient care.
Question: How many appointments does each doctor have in the last month? Identify doctors with the highest number of appointments.  
Q2.
Hypothesis: Analyzing patient visit patterns helps in developing targeted care programs.
Question: Which patients have more than three visits in the past year? Identify patients who haven’t visited the hospital in the last year.  
Q3.
Hypothesis: Insights into treatment effectiveness can improve patient outcomes.
Question: What are the most common treatments? Calculate the average cost of treatments provided.  
Q4.
Hypothesis: Optimizing resource allocation improves overall hospital efficiency.
Question: Which doctor has the highest treatment success rate? Calculate the average number of patients seen by each doctor per day.

**Dataset Download:**
https://docs.google.com/spreadsheets/d/16CNGwT-beuTSjF89k_Pua7Mlv9LKKbZm6p-laBKweo4/edit?gid=1112593966#gid=1112593966

**Introduction** 

Download the dataset from the provided link. Explore the dataset to understand its structure and contents. Choose a theme or topic that you find interesting within the dataset (e.g., sales, demographics, survey responses).

# Answering Hypothesis-Based Questions

To answer the hypothesis "Customers of different age groups prefer different types of accounts (e.g., Savings, Current, Salary, OverDraft)" and the corresponding question "What is the distribution of account types across different age groups?" using Power BI, follow these steps:

*Step-by-Step Solution that you have to Perform:*

1. *Load the Data:*
    - Import the banking dataset into Power BI.
2. *Data Preparation:*
    - Ensure the dataset includes the necessary columns: Customer Age, Account Type, and any other relevant fields.
    - Clean the data if needed, handling any missing values or inconsistencies.
3. *Create Age Groups:*
    - Use Power BI's data transformation tools to create age groups. For example:
        - 18-25
        - 26-35
        - 36-45
        - 46-60
        - 60+
4. *Build the Visualization:*
    - Use a *Stacked Column Chart* or *Clustered Bar Chart* to display the distribution of account types across different age groups.
    - Set the X-axis to represent the age groups and the Y-axis to represent the count or percentage of each account type.
    - Use different colors to represent different account types for clear differentiation.
5. *Customize the Chart:*
    - Add labels to show the exact counts or percentages on each bar.
    - Include a legend to indicate which color corresponds to which account type.
    - Use titles and axis labels to make the chart self-explanatory.
6. *Add Insights:*
    - Include a card or text box on the report page with a brief summary of your findings.
    - Highlight key insights such as which age group prefers which type of account the most.

*Example Analysis: (things to include in your report)*

*Visualization:*

- *Stacked Column Chart* with:
    - X-axis: Age Groups (e.g., 18-25, 26-35, etc.)
    - Y-axis: Count of Account Types
    - Legend: Account Types (Savings, Current, Salary, OverDraft)

*Findings:*

- The 18-25 age group prefers Savings accounts the most.
- The 26-35 age group shows a higher preference for Salary accounts.
- The 46-60 age group has a significant number of Current accounts.

If different age groups have the same preference, you can write them together.

*Answer (Summary):*

In our analysis, we found distinct preferences for account types among different age groups. Young adults (18-25) predominantly prefer Savings accounts, while those in the 26-35 age group lean towards Salary accounts. Older adults (46-60) show a preference for Current accounts. These insights can help tailor marketing strategies and product offerings to better meet the needs of each demographic group.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality", "column data type" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : There should not be any blank/empty dataset , null values & duplicate data.
