Exploratory Data Analysis (EDA) Using Pandas

Overview
This project performs Exploratory Data Analysis (EDA) on a dataset of roller coasters. EDA is a crucial step in data analysis, aimed at understanding the structure and relationships within the data through statistical summaries and visualizations. This repository includes the process for exploring roller coaster data, focusing on understanding feature distributions, relationships, and key insights.

Steps
Step 0: Imports and Reading Data

* Imports: Libraries for data manipulation and visualization are imported, including Pandas, NumPy, Matplotlib, and Seaborn.
* Read Data: The dataset is loaded from a CSV file.

Step 1: Data Understanding

* Shape: Displays the dimensions of the DataFrame.
* Head and Tail: Shows the first and last few rows of the DataFrame.
* Data Types: Lists the data types of each column.
* Describe: Provides summary statistics of the numeric columns.


Step 2: Data Preparation

* Dropping Columns: Removes irrelevant columns to focus on the essential data.
* Renaming Columns: Updates column names for clarity and consistency.
* Handling Missing Values: Identifies and manages missing values in the dataset.
* Removing Duplicates: Checks for and removes duplicate rows to ensure data integrity.

Step 3: Feature Understanding (Univariate Analysis)

* Plotting Feature Distributions: Analyzes individual feature distributions using histograms, KDE plots, and boxplots to understand their characteristics and spread.

Step 4: Feature Relationships

* Scatterplots: Visualizes the relationship between different features to identify correlations and patterns.
* Heatmap Correlation: Shows the correlation between selected features to understand their relationships.
* Pairplot: Displays pairwise relationships in the dataset, providing insights into how features interact with one another.

Step 5: Ask a Question About the Data

* Analysis: Determines locations with the fastest roller coasters, provided there are at least 10 coasters per location. This analysis helps identify where the most thrilling coasters are located based on their speed.

How to Use

Clone this repository to your local machine.

* Ensure you have the required libraries installed (pandas, numpy, matplotlib, seaborn).
* Place your dataset in the specified path (/content/coaster_db.csv).
* Run the Jupyter Notebook or Python script to execute the EDA steps.

Dependencies:

* pandas
* numpy
* matplotlib
* seaborn

License:
This project is licensed under the MIT License. See the LICENSE file for details.

