# Bike_Sales_Dashboard_Excel
An excel project to analyze and visualize the sales data of a bike store across different regions

## Business Context
This project was created for a bike store that sells bikes across different regions of the world.
The store has sales data for different purchases, with a focus on the clientele information including their age, income, location etc.

## Project Objective
With this data, the store owner would like to have a better understanding of the different demographics of their clientele.
They would like to know what kind of clients are purchasing their bikes.

## Business Problem
Sales data exists, but is not structured well to give a quick insights on "who" is interested in their product.

## Stakeholders
Bike store manager

## Business Requirements
To have a better understanding of how different demographics of their clientele affects their purchasing power.

### Functional Requirements
The solution should showcase the difference in purchasing power in terms of client income.</br>
The solution should allow the user to apply preferred filters depending on the marital status, occupation, and region of the buyer.</br>
The solution should be able to show how the commute distance affects the buyers choice of purchase</br>


### Non-Functional Requirements
The users will have access to the dashboard but not the dataset feeding the dashboards.</br>
There will be one data manager who updates the dataset with new sales records.</br>


## Dataset Used
### Source
The data used was a demo dataset.

- <a href="https://github.com/Estyell/Sales_Tracking_Dashboard/blob/main/DemoDashboard_Data.xlsx">Dataset</a>

### Cleaning & Transformations
#### Key Assumptions
Each row represents one sales transaction

#### Process
•	Removed duplicate records – 26 rows</br>
• Convert M to married and S to single under Marital Status column; M to male and F to Female under Gender column for easier reading</br>
• Created a new column (age_bracket) from Age column to condense the age data for easier reading – using a nested IF statement.
• The Commute Distance was not sorting the data in order because of the “10+ Miles”, putting it in the second position, this was converted to “More than 10 miles” so it can appear at the bottom
•	Ensure the data is consistent and clean with respect to data types, data format, and data values used.

### Tools Used
Microsoft Excel


## Business Questions
•	Does the income of buyers influence their purchasing power?</br>
•	Does the commuting distance of the buyer affect their bike purchase decision?</br>
•	How does the age bracket of the buyer infuence their buying decision?</br>


## Dashboard Created
-Dashoard Interaction	<a href="https://github.com/Estyell/Bike_Sales_Dashboard_Excel/blob/main/Dashboard.png">View_Dashboard</a>


## Dashboard
