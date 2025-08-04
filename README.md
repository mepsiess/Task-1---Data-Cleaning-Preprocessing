# Task 1 - Data Cleaning Preprocessing
#### Aim: Learning how to clean and prepare raw data for Machine Learning using relevant tools and libraries of Python including Pandas, NumPy, Matplotlib / Seaborn.

# **Introduction**
This project focuses on cleaning and preprocessing the Titanic dataset. Real-world data is often messy, incomplete, or inconsistent. Before applying any machine learning models, it’s essential to prepare the data properly so that the model can learn meaningful patterns.

In this project, I performed several preprocessing tasks, including:
- Handling missing values
- Encoding categorical values
- Scaling numerical data
- Visualizing survival statistics

The steps taken reflect the real world challenges faced in data cleaning and lay a solid foundation for building predictive models in later stages.


# Learning Outcomes

1. **Data Cleaning**: The process of identifying and modifying errors and inconsistencies in data to improve its quality. Data Cleaning includes tasks like removing irrelevant columns, correcting data types and checking for duplicates or outliers.

2. **Handling Missing Values**: A method used to deal with gaps or empty entries in datasets. Common techniques include filling missing numerical values with mean, median and mode, or removing rows/columns with too many missing values.
3. **Encoding Categorical Values**: The process of converting categorical (non-numerical) data into a numerical format so that it can be used by maching learning (ML) algorithms. This includes label encoding for binary categories and one hot encoding for variables with multiple categories.
4. **Feature Scaling**: A techinque to normalize the range of independent variables (features). It ensures that no single feature dominates the others due to differences in units or magnitude. Common methods include Min-Max normalization and standardization (z-score scaling).


# **Step-by-Step Explanation**

#### Step 1: Importing and Exploring the Dataset
The dataset was loaded using the `pandas` library. This step involves reading the CSV file into a DataFrame, which provides a structured, tabular form of the data that can be easily analyzed and manipulated.
```
import pandas as pd
df = pd.read_csv("Titanic-Dataset.csv")
```

Initial exploration helps you understand the structure, data types, and missing values in the dataset. Methods like `.info()`, `.describe()`, and `.isnull().sum()` are used to summarize data characteristics.
