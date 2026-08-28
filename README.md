# 🚢 Titanic Survival Analysis - Task 

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** and **data preprocessing** using the Titanic dataset. The main objective is to understand the dataset, identify missing values, clean the data, and prepare it for future machine learning tasks.

The project includes data loading, inspection, missing value handling, preprocessing, and basic data visualization using Python.

---

## 📁 Dataset

The project uses the standard **Titanic dataset (`train.csv`)**, which contains information about passengers aboard the Titanic.

The dataset includes features such as:

* Passenger ID
* Survival Status
* Passenger Class
* Name
* Gender
* Age
* Number of Siblings/Spouses
* Number of Parents/Children
* Ticket Number
* Fare
* Cabin
* Port of Embarkation

The dataset is available from the **Kaggle Titanic Competition**.

---

## 🧪 Tasks Performed

### 1. Data Loading and Inspection

The dataset was loaded using the **Pandas** library.

The following methods were used to understand the dataset structure:

* `.head()` – To view the first few records.
* `.info()` – To check data types and missing values.
* `.unique()` – To identify unique values in selected columns.
* `.isnull().sum()` – To check the number of missing values.

---

### 2. Missing Value Handling

Missing values were handled as follows:

#### Age

Missing values in the `Age` column were replaced using the **median age**.

#### Cabin

The `Cabin` column contained a large number of missing values, so it was removed from the dataset.

#### Embarked

Missing values in the `Embarked` column were filled using the **most frequent value (mode)**.

---

### 3. Data Preprocessing

The following preprocessing steps were performed:

* Identified and handled missing values.
* Filled missing values in the `Age` column using the median.
* Filled missing values in the `Embarked` column using the mode.
* Removed the `Cabin` column due to excessive missing data.
* Verified the dataset after cleaning.

These preprocessing steps help improve data quality and prepare the dataset for future machine learning models.

---

### 4. Data Visualization

A basic visualization was created using **Matplotlib** to analyze the distribution of passenger ages.

This visualization helps provide an initial understanding of the age-related patterns present in the dataset.

---

## 📊 Technologies and Libraries Used

* **Python**
* **Pandas**
* **Matplotlib**

---

## 📂 Project Structure

```text
Titanic-Survival-Analysis/
│
├── train.csv
├── Titanic_Survival_Analysis.ipynb
├── Task 1 Report.pdf
└── README.md
```

---

## 📈 Key Learnings

Through this project, the following concepts were explored:

* Loading datasets using Pandas.
* Inspecting dataset structure.
* Identifying missing values.
* Handling missing data using median and mode.
* Dropping unnecessary columns.
* Performing basic data preprocessing.
* Creating simple visualizations using Matplotlib.

---

## ✅ Conclusion

The Titanic dataset was successfully explored and preprocessed.

Key outcomes of this project include:

* Missing values were identified and handled appropriately.
* The `Cabin` column was removed due to a high number of missing values.
* Missing `Age` values were filled using the median.
* Missing `Embarked` values were filled using the mode.
* A basic visualization was created to understand the age distribution of passengers.

The cleaned dataset is now ready for further analysis, feature engineering, and machine learning model development.

---

## 🚀 Future Improvements

The following improvements can be implemented in future versions of the project:

* Encode categorical variables such as `Sex` and `Embarked`.
* Perform detailed exploratory data analysis.
* Analyze survival rates based on gender.
* Analyze survival rates across passenger classes.
* Create age groups for better analysis.
* Perform feature engineering.
* Build machine learning models such as:

  * Logistic Regression
  * Decision Tree
  * Random Forest
* Evaluate and compare model performance.

---

## 📌 Project Status

**Completed – Task : Data Analysis and Preprocessing**

The project is ready for the next phase of machine learning model development.

---

## 👨‍💻 Author

**Dharshini M**

B.Tech – Artificial Intelligence and Data Science
Aspiring Software Developer | AI & Data Science Enthusiast
