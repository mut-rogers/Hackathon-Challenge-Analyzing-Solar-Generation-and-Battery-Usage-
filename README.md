
## A Hackathon Challenge: Analyzing Solar Generation and Battery Usage 

Create a project that analyzes solar electricity generation, electricity usage, and battery usage data to understand the potential benefits of using a battery system to store excess solar electricity. 

The participants are required to utilize SQL and Python programming language and various libraries, including pandas for data manipulation, numpy for numerical operations, matplotlib for data visualization, and datetime for handling time-related data.


You can download the data for this project here, (it is an excel workbook) 

 https://github.com/HarunMbaabu/Data-Analyst-Assessment/blob/main/Junior%20Data%20Analyst%20_%20Data.xlsx 

### Expected 
 - Perform data visualization and checks
 - Calculate the Electricity Bought
 - Calculating Excess Solar Generation.
 - Model the Battery Charge Level


## Project Overview
This project involves analyzing solar electricity generation, electricity usage, and battery usage data to understand the potential benefits of using a battery system to store excess solar electricity. The project utilizes the Python programming language and various libraries, including pandas for data manipulation, numpy for numerical operations, matplotlib for data visualization, and datetime for handling time-related data 

## Implementation Steps 
- #1 Data Visualization and Checks 
    The project begins by loading the provided data from an Excel file (Junior Data Analyst _ Data.xlsx) into a pandas DataFrame. 

    The data contains information about solar electricity generation, electricity usage, and other relevant parameters. The goal of this step is to visualize and compare the average solar electricity generation and electricity usage for each hour in a day. 

- #2 Calculating Electricity Bought 
    In this step, the project calculates the electricity needed to be bought from the provider by subtracting the solar electricity generation from the electricity usage. The numpy library is used to efficiently perform element-wise subtraction and limit the result to non-negative values.



