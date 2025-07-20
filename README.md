# Student Depression Prediction Project

This project was developed as the final assignment for the **Big Data Analysis** course. It leverages **Apache Spark** to process and analyze a dataset related to mental health and depression, with a focus on **students** as the target population.

## Project Objective

To preprocess and analyze large-scale data using distributed computing techniques in Spark, with the goal of identifying key factors that correlate with depression among students.

## Dataset

- **Source**: Student Depression Dataset (CSV format)
- **Content**: The dataset includes multiple attributes related to demographics, profession, and mental health indicators.
- **Preprocessing**: 
  - Filtered to retain only rows where the profession is `Student`.
  - Removed irrelevant or noisy columns.
  - Cleaned and standardized data for analysis.

## Technologies Used

- Apache Spark (PySpark)
- Python 3
- Jupyter Notebook
- Pandas (for minor local operations)
- Matplotlib / Seaborn (if used)

## Key Steps

1. **Spark Session Initialization**  
   Set up a Spark environment for distributed processing.

2. **Data Loading**  
   Load the dataset using Spark’s `read.csv()` method.

3. **Filtering**  
   Select only the student-related entries for focused analysis.

4. **Data Cleaning**  
   Drop irrelevant columns and handle missing or malformed values.

5. **Feature Engineering**  
   Prepare features that might be predictive of depression.

6. **Exploratory Data Analysis (EDA)**  
   Visualize distributions, correlations, and trends.

7. **Modeling (if included)**  
   Apply machine learning models such as Logistic Regression or Decision Trees using Spark MLlib.

## Results

(Insert here a summary of key insights or performance metrics if any models were applied.)

## Conclusion

This project demonstrates how Apache Spark can be used for efficient processing of real-world mental health data. By narrowing the focus to students, it aims to reveal patterns that can support mental health interventions in academic settings.

## Authors

Yuval Hoffman & Daniel Loevetski
Big Data Analysis Course – Final Project
