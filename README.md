# Pizza-Weekly-Financials-Power-BI
Revealing Weekly Pizza sales statistics 

## Table Of Contents

- [ Project Overview ](#Project-Overview)
- [ Data Source ](#Data-Source)
- [ Tools ](#Tools)
- [ Data Extraction and Cleaning ](#Data-Extraction-and-Cleaning)
- [ Data Modelling ](#Data-Modelling)
- [ Data Visualisation ](#Data-Visualisation)
- [ Explanatory Data Analysis](#Explanatory-Data-Analysis)
- [ Findings ](#Findings)

### Project Overview

This project seeks to deliver insights for Weekly Pizza Sales against the daily target.

### Data Source
Pizza Data:A csv file provided by the organisation ,which contains the relevant data for analysis and comparison.

### Tools
- Power BI 


### Data Extraction and Cleaning
1. Extract the CSV file (Pizza Data) into Power BI.
2. Load and transform the data using Power Query.
3. Address any missing values.
4. Standardize data formatting.

   ### *Load Data*
  

### Data Modelling
1. Identity the number of Dimension Tables and Facts tables for the dataset
2. Create the necessary Dimension Tables.
3. Normalize the Fact Table and rename it to FactPizza, then close and apply changes in the Power Query Mode
4. Navigate to the modeling page by clicking the leftmost option on the home tab.
5. Establish a Star Schema model by creating relationships between the Fact Table and the Dimension Tables.
6. Use the drag-and-drop method to define these relationships.

   ### *Relationship Model*
  

### Data Visualisation
1. Create a DAX Measures Table containing calculations for CSP Rate and PAYG Rate for report visualizations (for comparisons).
2. Design the report theme.
3. Select appropriate visualizations and format them according to the theme.
4. Conduct tests on the report.

   ### *Dashboard*

<img width="1587" height="611" alt="image" src="https://github.com/user-attachments/assets/d4acca48-e0b3-44c5-a8ac-3384b9a35872" />


    



### Explanatory Data Analysis
- Analyze costs per subscriptionName, MeterCategory, and ResourceGroup.
- Assess potential savings/costs using the CSP Rate.

### Findings
- The Pizza Core Production Subscription represents the highest liability to the organization when using the PAYG Rate.
- Transitioning to CSP yields significant savings for the company(about 7% less than PAYG)


### Recommendation
1. I recommend the company switch to the CSP Rate, as it demonstrates a substantial reduction in costs compared to PAYG.
2. Increase the use of compute engines over storage to further minimize expenses.
