# Diwali Data Analysis-Exploratory Data Analysis
In this Project I learned Python project on Diwali sales data analysis, covering environment setup, data cleaning, and exploratory data analysis using libraries like Pandas and Matplotlib. 
It guides users through analyzing sales trends by 
gender,
age,
state,
marital status,
occupation, 
and product category, 
concluding with a summary of insights.


This project provides a step-by-step guide on performing exploratory data analysis (EDA) using Python, specifically focusing on a Diwali sales dataset. The project is designed for beginners and covers everything from setting up the Python environment to interpreting data insights.

Here's a breakdown of the key areas covered:

Project Overview and Data: The project introduces a Diwali sales dataset, explaining the goal of analyzing customer purchasing behavior to enhance customer experience and increase revenue.

Python and Jupyter Notebook Setup:
Installation of Python: Instructions for downloading and installing Python, emphasizing the importance of adding Python to the system's PATH.
Jupyter Notebook Installation and Basics: Guides on installing Jupyter Notebook and a quick overview of its interface, including how to create new files, run cells, and save work.
Reading of csv file: The project demonstrates how to read the Diwali sales dataset (CSV file)

Importing Libraries:It Explains how to import essential Python libraries like NumPy, Pandas, Matplotlib, and Seaborn for data manipulation and visualization.(through pip install)
Loading Data: Shows how to load the CSV data into a Pandas DataFrame and check its dimensions using df.shape.
Inspecting Data Types and Missing Values: Uses df.info() to understand data types and identify missing values, and df.isnull().sum() to count nulls.

## Data Cleaning

Handling Missing Data and Unnecessary Columns:Demonstrates how to drop columns with all null values and remove rows with missing data using df.drop() and df.dropna().

Data Type Conversion: Explains how to convert the 'Amount' column from float to integer type using astype(int).

Renaming Columns and Descriptive Statistics: Shows how to rename columns using df.rename() and how to generate descriptive statistics for numerical columns using df.describe().

## Exploratory Data Analysis (EDA)

Gender Analysis : Visualizes the distribution of buyers by gender and analyzes purchasing power, concluding that females are the primary buyers with higher purchasing power.

####  Age Group Analysis:
Examines purchasing behavior across different age groups, identifying the 26-35 age group as the most active buyers, particularly females.

#### State-wise Analysis:
Analyzes sales distribution across states, highlighting Uttar Pradesh, Maharashtra, and Karnataka as top-performing states.

#### Marital Status Analysis: 
Investigates purchasing patterns based on marital status, revealing that married women are the highest spenders.

#### Occupation Analysis: 
Explores purchasing behavior by occupation, indicating that individuals in IT, healthcare, and aviation sectors are significant contributors to sales.

#### Product Category Analysis:
Identifies the top-selling product categories as Food, Clothing, and Electronics.

#### Top Selling Products:
Pinpoints specific top-selling products using nlargest().

#### Final Summary:

### Married women age group 26-35 yrs from U.P,Maharastra and Karnataka working in IT,Healthcare and Aviation 
### are more likely buy products from Food,Clothing and Electronics category.
