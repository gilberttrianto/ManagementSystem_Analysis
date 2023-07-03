# ManagementSystem_Analysis
# Austin Smart City Waste Disposal and Waste Management System Analysis

## Description

### Objective
Analysis of the Waste Disposal and Management System in Austin Smart City City in 2021 uses the collection of selected data and drawing conclusions based on sample data, as well as planning for the conditioning of the Waste Disposal and Management System in the future.

### Problem Statement
Based on the conditions for the disposal and management of waste in the city of Austin City, analysis is needed to determine the conditions that occur in each site of waste disposal and plan for the calculation or plan for the disposal and management of waste in the city of Austin City.

The dataset used is taken from Google Cloud 'Bigdataquery' / SQL Bigquery with the topic of Austin_Waste
The data taken, processed using the query as follows:

SELECT report_date,load_time, load_type, load_weight, dropoff_site FROM `bigquery-public-data.austin_waste.waste_and_diversion` WHERE EXTRACT(YEAR FROM report_date) = 2021

## Conclusion, Assumptions, Overall Analysis

Based on the analysis that has been carried out, the need for new waste treatment and processing facilities due to waste disposal continues to increase. Based on the analysis of the average ratio of disposed and processed waste, there is no significant ratio of waste to disposed waste, in the sense that the waste disposal site can still accommodate the disposed waste.

The government is required to open a new site so that it can reveal a lot of processed waste in one place. The processing of waste delivery must also be evenly distributed in every place so that waste disposal can be processed properly. The capacity of the new site also needs to be considered so that it fits the needs and is in accordance with the analysis that has been carried out.

For the purposes of waste disposal analysis, calculation techniques are carried out using numerical methods. By using the v equation, obtained for the Derivative of the V value tomorrow's waste prediction.
Obtained predictions of waste that will be disposed of the next day in the city of Austin as much as 1255770.0 kg.
