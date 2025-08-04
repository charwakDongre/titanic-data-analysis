# titanic-data-analysis
# Titanic Data Cleaning and Preprocessing

This project focuses on cleaning and preparing the famous Titanic dataset for machine learning analysis. The entire process is documented in the `titanic_data_cleaning.ipynb` Jupyter Notebook.

---

## Dataset

The project uses the `Titanic-Dataset.csv` file, which contains passenger data from the Titanic disaster.

---

## Data Cleaning and Preprocessing Steps

The Jupyter Notebook covers the following data transformation steps:
- **Handling Missing Values**: Filled missing data in the 'Age' and 'Embarked' columns and dropped the 'Cabin' column due to a high number of missing values.
- **Feature Engineering**: Converted categorical features like 'Sex' and 'Embarked' into numerical format using one-hot encoding.
- **Feature Scaling**: Standardized numerical features ('Age', 'Fare', 'Pclass', etc.) to ensure they have a similar scale.
- **Outlier Removal**: Identified and removed outliers from the 'Age' and 'Fare' columns using the Interquartile Range (IQR) method to improve model performance.

---

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
