# Car_dataset_EDA
Exploratory Data Analysis (EDA) of a Car Dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn to analyze vehicle features, identify patterns, explore car price trends, and visualize meaningful insights.

🚗 Car Dataset – Exploratory Data Analysis (EDA)

1. Project Introduction

Exploratory Data Analysis (EDA) is an important process in data science that helps us understand, analyse and interpret datasets.

This project focuses on performing Exploratory Data Analysis on a Car Dataset using Python. The dataset contains information about different car brands, models, colours, countries and years of manufacture.

The main purpose of this project is to explore the dataset, identify patterns, understand the distribution of car-related information and represent the findings through data visualizations.

2. Project Objectives

The main objectives of this project are:

- To understand and explore the given car dataset.
- To identify different car brands and models.
- To analyse the distribution of cars across different countries.
- To study car manufacturing years.
- To check for missing values and duplicate records.
- To identify possible outliers in numerical data.
- To perform data visualization using Python libraries.
- To extract meaningful insights from the dataset.

3. Dataset Description

The dataset used in this project is a Car Dataset containing 30,000 records and 8 columns.

It provides information about vehicles and associated records.

Dataset attributes

Column Name| Description
First Name| First name associated with the record
Last Name| Last name associated with the record
Country| Country associated with the record
Car Brand| Manufacturer or brand of the car
Car Model| Model of the vehicle
Car Color| Colour of the car
Year of Manufacture| Year in which the car was manufactured
Credit Card Type| Credit card category associated with the record

Dataset size:

- Total records: 30,000
- Total columns: 8
- Numerical columns: 1
- Categorical columns: 7

4. Libraries Used

The following Python libraries are used in this project:

1. Pandas

- Used for reading and manipulating datasets.
- Helps in analysing rows and columns.
- Used for checking missing values and duplicates.

2. NumPy

- Used for numerical operations.
- Supports mathematical calculations and data processing.

3. Matplotlib

- Used to create graphs and visual representations.
- Helps in understanding data patterns.

4. Seaborn

- Used for statistical data visualization.
- Helps create boxplots and other graphical representations.

5. Scikit-learn

- Used for Label Encoding.
- Converts categorical values into numerical representations.

5. Exploratory Data Analysis

The following steps are performed during the analysis:

Step 1: Importing Libraries

Importing the required Python libraries such as Pandas, NumPy, Matplotlib and Seaborn.

Step 2: Loading the Dataset

The dataset is loaded using the Pandas "read_csv()" function.

Step 3: Understanding the Dataset

Functions such as "head()", "tail()" and "info()" are used to examine the dataset and understand its structure.

Step 4: Checking Missing Values

The "isnull().sum()" function is used to identify missing values in each column.

Step 5: Checking Duplicate Records

The "duplicated().sum()" function is used to identify repeated records.

Step 6: Outlier Detection

A boxplot is used to examine the numerical data and identify possible outliers.

Step 7: Label Encoding

Label Encoding is applied to convert categorical columns into numerical values for further analysis.

Step 8: Univariate Analysis

The distribution of car brands is explored using a histogram.

6. Data Visualizations

Visualizations help us understand the dataset in a simple and effective manner.

The following visualization is included in the project:

1. Boxplot – Outlier Detection

A boxplot is used to examine the numerical column, Year of Manufacture, and identify possible outliers.

2. Histogram – Distribution of Car Brands

A histogram is used to visualize the distribution of car brands after label encoding.

These visualizations help in understanding the distribution and characteristics of the dataset.

7. Key Findings

Based on the exploratory analysis, the following findings were observed:

- The dataset contains 30,000 records and 8 columns.
- There are no missing values in the dataset.
- No duplicate records were identified in the duplicate check.
- The dataset contains 78 unique car brands.
- It contains 1,006 unique car models.
- There are 19 different car colours.
- The dataset covers 230 countries.
- The manufacturing years range from 1909 to 2013.
- Boxplot analysis is used to examine possible outliers.
- Label Encoding helps convert categorical data into numerical form.

8. Conclusion

The Car Dataset Exploratory Data Analysis project provides a practical understanding of how Python can be used to explore and analyse structured data.

Through this project, we learned how to load datasets, understand data structures, identify missing and duplicate values, detect possible outliers and perform data visualization.

The use of Pandas, NumPy, Matplotlib, Seaborn and Scikit-learn makes data analysis easier and more effective.

Overall, this project helped us develop practical knowledge of Python programming, data handling, visualization and the fundamentals of data science.
