# Data-Analyzing-Project
# Employee Data Analysis Project

# Project Overview
This project involves the analysis of employee data to gain insights and perform data preprocessing. The dataset includes information about employees such as their personal details, employment history, and resignation information. The main goals of this project are as follows:

  1. Data Cleaning: Clean the dataset by handling missing values and data types.
  2. Data Exploration: Explore the dataset to understand the distribution of various attributes.
  3. Data Visualization: Visualize key findings using graphs and charts.
  4. Data Export: Save the preprocessed data to a CSV file.
     
# Files in the Repository
  employee_preprocess.ipynb: Jupyter Notebook containing the Python code for data analysis and preprocessing.
  employees.csv: Dataset containing employee information.
  holidays.csv: Dataset containing holiday information (assumed to be part of the project but not present in the provided code).
  leaves.csv: Dataset containing leave information (assumed to be part of the project but not present in the provided code).
  salary.csv: Dataset containing salary information (assumed to be part of the project but not present in the provided code).
  employee_preprocess_200623P.csv: CSV file containing the preprocessed employee data.
Project Steps
Data Loading: The project begins by reading the employee data from the provided CSV file using the Pandas library.

Data Cleaning:

Handling missing values in the dataset, particularly in the 'Marital_Status' and 'Year_of_Birth' columns.
Replacing invalid 'Year_of_Birth' values with the median year.
Filling missing 'Marital_Status' values based on the mode within gender and religion groups.
Data Transformation:

Splitting the 'Date_Resigned' column into month, day, and year, and extracting the 'Resigned_Year'.
Cleaning and formatting the 'Resigned_Year' column by removing '.0' and adding '20' to the year values.
Filtering out rows with 'Resigned_Year' values as '20nan'.
Data Visualization:

Creating bar charts to visualize the number of resignations by year and distribution of employment categories.
Creating a pie chart to visualize the distribution of marital statuses.
Creating a bar chart to visualize the number of joinings by year.
Creating bar charts to visualize the distribution of employment types and the relationship between employment type and employee status.
Data Export:

Saving the preprocessed employee data to a CSV file for future analysis.
Dependencies
To run the code in the Jupyter Notebook, you need the following Python libraries installed:

pandas
numpy
matplotlib
seaborn
Usage
Clone this repository to your local machine.
Open the Jupyter Notebook employee_preprocess.ipynb.
Execute the code cells in the notebook to perform the data analysis and preprocessing.
The preprocessed data will be saved as employee_preprocess_200623P.csv.
