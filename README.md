🚢 Titanic Dataset - Data Cleaning & Preprocessing

This project focuses on preparing the Titanic dataset for machine learning by performing data cleaning and preprocessing tasks using Python and popular data science libraries.

🎯 Objective

To clean and preprocess the Titanic dataset by:

Handling missing values
Encoding categorical variables
Scaling numerical features
Detecting and removing outliers

📁 Project Structure

/titanic-data-cleaning
  │ ├── titanic.csv # Dataset file 
    ├── titanic_preprocessing.ipynb # Main Jupyter notebook 
    └── README.md # Project overview and instructions

🛠️ Tools & Libraries Used

-Python
Pandas – data manipulation
NumPy – numerical operations
Seaborn & Matplotlib – data visualization
Scikit-learn – preprocessing (scaling, encoding)

🧪 Steps Performed

1. Loaded the Titanic dataset
2. Explored basic information about the data (nulls, data types, stats)
3. Handled missing values:
   -Filled Age with the median
   -Filled Embarked with the mode
   -Dropped Cabin (too many missing values)
4. Converted categorical variables:
  -Sex: label encoding (male → 0, female → 1)
  -Embarked: one-hot encoding
5. Standardized numerical columns (Age and Fare) using StandardScaler
6. Visualized and removed outliers in Fare using a boxplot
7. Final data inspection** with .info() and .head()
   
📊 Sample Output

A sample of the cleaned DataFrame after preprocessing:

| Survived | Pclass | Sex | Age  | SibSp | Parch | Fare | Embarked_Q | Embarked_S |
|----------|--------|-----|------|-------|-------|------|------------|------------|
| 0        | 3      | 0   |-0.55 | 1     | 0     |-0.50 | 0          | 1          |
| 1        | 1      | 1   | 0.60 | 1     | 0     | 0.65 | 0          | 0          |
| ...      | ...    | ... | ...  | ...   | ...   | ...  | ...        | ...        |

✅ How to Run

Clone this repo or download the files
Make sure titanic.csv is in the project directory
Open titanic_preprocessing.ipynb in VS Code or Jupyter
Run each cell in order to process the dataset

📝 Notes

-This project was completed as part of the Elevate Lab AI/ML Internship.
-The data used is from the public Titanic Dataset on Kaggle.

🙌 Acknowledgements

Thanks to Elevate Lab for the opportunity and resources to complete this task!
