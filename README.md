# Titanic Data Analysis Project

This repository contains a data analysis project on the famous Titanic dataset. The goal is to explore the data to understand the factors that influenced passenger survival and to prepare the dataset for potential machine learning modeling. The entire workflow, from cleaning the raw data to uncovering insights, is documented in the Jupyter Notebook.

---

## Analysis Workflow

The project follows a standard data analysis process:

### 1. Data Cleaning and Preprocessing
The initial raw dataset required several cleaning and preparation steps to make it suitable for analysis:

- **Handling Missing Values**: Missing data in the 'Age' and 'Embarked' columns were filled using the median and mode, respectively. The 'Cabin' column was dropped due to a high number of missing entries.
- **Feature Engineering**: Text-based categorical features ('Sex', 'Embarked') were converted into a numerical format using one-hot encoding.
- **Outlier Removal**: Outliers in the 'Age' and 'Fare' columns were identified and removed using the Interquartile Range (IQR) method to prevent them from skewing the analysis.
- **Feature Scaling**: Numerical features were standardized to a common scale, a crucial step for many machine learning algorithms.

### 2. Exploratory Data Analysis (EDA)
After cleaning the data, an exploratory analysis was performed to discover patterns and relationships.

#### Key Insights Discovered:
- **Overall Survival**: Only about **38%** of the passengers in this dataset survived the tragedy.
- **Survival by Gender**: A passenger's gender was a major factor in their survival. **Females had a significantly higher chance of survival** compared to males.
- **Survival by Class**: There was a strong correlation between a passenger's class and their survival. **First-class passengers had the highest survival rate**, while third-class passengers had the lowest.

---

## Libraries Used

This project relies on the following Python libraries:

- **pandas** for data manipulation and analysis.
- **numpy** for numerical operations.
- **matplotlib** & **seaborn** for data visualization.
- **scikit-learn** for data preprocessing tools.
