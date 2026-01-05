# Titanic Exploratory Data Analysis (EDA)

##  Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand
the key factors that influenced passenger survival. The analysis focuses on data cleaning,
visualization, and insight generation using Python-based data analysis libraries.

This project was completed as part of **Week 1 – Data Science Internship tasks**.

---

##  Dataset Information
- **Dataset Name:** Titanic Dataset
- **Source:** Kaggle – Titanic: Machine Learning from Disaster
- **File Used:** `train.csv`
- **Total Records:** 891
- **Total Features:** 12 (before cleaning)

The dataset contains information such as passenger age, gender, ticket class, fare,
embarkation port, and survival status.

---

##  Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Steps Performed

### 1. Data Loading & Inspection
- Loaded the dataset using Pandas
- Inspected structure, data types, and missing values

### 2. Data Cleaning
- Dropped irrelevant columns (`PassengerId`, `Ticket`, `Cabin`)
- Filled missing values:
  - `Age` using median
  - `Embarked` using mode
- Verified dataset contained no missing values

### 3. Exploratory Data Analysis(EDA)
- Survival distribution analysis
- Survival comparison by:
  - Gender
  - Passenger class
  - Age
  - Fare
- Distribution analysis of numerical features
- Correlation analysis using heatmap

### 4. Insight Generation
- Interpreted visual patterns
- Identified key survival factors

---

##  Key Insights
- Female passengers had significantly higher survival rates than male passengers.
- Passengers traveling in higher classes were more likely to survive.
- Younger passengers showed slightly better survival probabilities.
- Higher fare values were associated with increased chances of survival.
- Socio-economic factors played a major role in survival outcomes.

---

##  Conclusion
This exploratory data analysis highlights the importance of demographic and socio-economic
factors in determining passenger survival on the Titanic. The cleaned dataset and insights
derived from this analysis can serve as a strong foundation for further predictive modeling
and machine learning applications.

##  Project Structure
Titanic-EDA/
│
├── Dataset/
│ ├── train.csv
│ ├── test.csv
│ └── gender_submission.csv
│
├── notebooks/
│ └── Titanic_EDA.ipynb
│
├── .gitignore
└── README.md

 ## Author
**Prathamesh Patil**  
GitHub: https://github.com/pppatil3p