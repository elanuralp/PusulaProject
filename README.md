# Pusula Project - Drug Side Effects Analysis and Preprocessing

## Project Overview
This repository contains a data science project focused on analyzing and preprocessing a dataset related to drug side effects. The main goal is to perform thorough data exploration, handle missing values, engineer meaningful features, and preprocess the data to prepare it for further predictive modeling.

## Key Steps
### 1. Exploratory Data Analysis (EDA)
In the initial phase, the dataset was explored to:
- Understand its structure, variable types, and distribution.
- Detect missing values, outliers, and anomalies.
- Visualize key variables to identify patterns and trends, particularly around age, medication duration, and side effects.

### 2. Data Preprocessing
Several important preprocessing steps were taken to clean and prepare the data for modeling:
- **Age Calculation**: Derived from the patient's date of birth and validated to remove unrealistic values (ages under 0 or over 120).
- **Medication Duration**: Computed from medication start and end dates, with invalid or negative values removed.
- **Class Imbalance Handling**: Rare side effects were grouped into an "Other" category to reduce class imbalance and improve model performance.
- **Feature Engineering**: Created a Body Mass Index (BMI) feature from height and weight data.
- **Categorical Encoding**: Applied One-Hot Encoding to gender and city columns, grouping rare cities into an "Other" category to reduce dimensionality.

### 3. Results
The final dataset is well-structured and ready for model training. Key features have been transformed or engineered, and class imbalance issues have been addressed to improve model accuracy.

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/elanuralp/PusulaProject.git
2. **Install dependencies**: Make sure to have the following libraries installed:
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
You can install these libraries using pip:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the Notebook: Open the Jupyter Notebook to explore the analysis and preprocessing steps:
   ```bash
   jupyter notebook EDA.ipynb
4.Check Preprocessed Data: The preprocessed dataset is included and ready for use in further steps like feature selection and model training.

## Future Work
* Model Training: The preprocessed data can now be used to build predictive models for drug side effects.
* Feature Selection: Further analysis to refine and select the most important features for modeling.
* Evaluation: Train, evaluate, and optimize various machine learning models to predict side effects.

## Author
Ela Nur ALP   
Email : elanur714@gmail.com



