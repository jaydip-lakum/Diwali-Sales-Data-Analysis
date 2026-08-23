#  Diwali Sales Data Analysis (EDA)

##  Project Overview
This project is an Exploratory Data Analysis (EDA) of a Diwali sales dataset using Python. The objective is to analyze customer purchasing behavior, demographic trends, and state-wise sales performance to help businesses make data-driven decisions and target the right audience.

##  Tech Stack & Tools
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

##  Data Cleaning & Transformation
* Removed empty and irrelevant columns (`Status`, `unnamed1`).
* Handled missing values by dropping nulls to ensure accurate analysis.
* Converted data types for accurate calculations (e.g., `Amount` to integer).
* Renamed columns for better readability (e.g., `Marital_Status` to `Shaadi`).

##  Key Exploratory Insights
* **Gender & Age:** Females possess a significantly higher purchasing power than males. The majority of the buyers belong to the **26-35 years** age group, predominantly females.
* **Top States:** **Uttar Pradesh, Maharashtra, and Karnataka** generated the highest number of orders and the maximum total sales amount.
* **Marital Status:** Married women are the highest contributors to overall sales.
* **Occupation & Categories:** Employees in the **IT, Healthcare, and Aviation** sectors are the top buyers.

##  Files in this Repository
* `Diwali_Sales_Analysis.ipynb`: The main Jupyter Notebook containing the Python code, data cleaning steps, and visualizations.
* `Diwali Sales Data.csv`: The raw dataset used for the analysis.
