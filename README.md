Titanic Survival Analysis - Task 1
This project is a basic exploratory data analysis (EDA) and preprocessing exercise using the Titanic dataset, aimed at preparing the data for future machine learning tasks.

📁 Dataset
We used the standard Titanic dataset (train.csv), available on Kaggle Titanic Competition.

🧪 Tasks Performed
1. Data Loading & Inspection
Loaded the dataset using pandas.
Inspected data using .head(), .info() and .unique() to understand the structure and identify missing values.
2. Missing Value Handling
Age: Filled missing values with the median.
Cabin: Dropped entirely due to high number of missing entries.
Embarked: Filled missing values with the most frequent (mode) entry.
3. Data Preprocessing
Cleaned up nulls to ensure data consistency.
Dropped unnecessary columns (e.g., Cabin).
Categorical encoding and additional preprocessing steps can be added in later phases.
4. Visualization
Created a basic line plot to visualize Age distribution across passengers using matplotlib.
📊 Libraries Used
pandas
matplotlib.pyplot
✅ Summary
The data is now cleaned and preprocessed.
Missing values were handled appropriately.
A simple age visualization was generated.
Dataset is ready for modeling or further feature analysis.
🚀 Next Steps (Optional Ideas)
Encode categorical variables (Sex, Embarked, etc.).
Build a predictive model (e.g., logistic regression or decision tree).
Analyze survival rates across gender, age groups, and class.
📌 Report
A full report in PDF format is included in this repository (Task 1 Report.pdf).
