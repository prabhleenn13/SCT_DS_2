# Titanic Dataset – Data Cleaning & Exploratory Data Analysis (EDA)

## Project Overview

This project was completed as part of my internship at **Skillcraft Technology**. The task involved performing **data cleaning** and conducting detailed **exploratory data analysis (EDA)** on the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data). The goal was to discover meaningful patterns and relationships that could help understand the factors affecting passenger survival.


## Tools & Libraries Used

- **Python**
- **Jupyter Notebook**
- `pandas` for data manipulation  
- `numpy` for numerical operations  
- `matplotlib` & `seaborn` for data visualization  


## Data Cleaning Process

- Handled missing values:
  - Filled `Age` with the median value
  - Filled `Embarked` with the mode (most common value)
- Dropped irrelevant or incomplete columns: `Cabin`, `Name`, `Ticket`, `PassengerId`
- Encoded categorical columns like `Sex` and `Embarked`
- Created a new feature:  
  - **FamilySize = SibSp + Parch + 1**


## Exploratory Data Analysis (EDA)

### Key Visualizations & Insights:

1. **Missing Data Heatmap**  
   Identified and visualized missing values in the dataset.

2. **Survival Count Plot**  
   Showed the number of survivors vs non-survivors.

3. **Survival by Gender**  
   Revealed that **females had a significantly higher survival rate** than males.

4. **Survival by Passenger Class**  
   First-class passengers had higher chances of survival compared to third-class passengers.

5. **Age Distribution**  
   Analyzed the distribution of ages among passengers.

6. **Age vs Survival**  
   Explored how survival likelihood changed across age groups.

7. **Fare Distribution**  
   Visualized the spread of ticket prices; high-paying passengers tended to survive more.

8. **Correlation Matrix (Heatmap)**  
   Highlighted relationships between numerical variables, including how **Fare**, **Pclass**, and **Sex** were linked to survival.

9. **Survival by Family Size**  
   Found that passengers with **1–3 family members** had better survival chances than those traveling alone or with large families.


## Dataset Source

- [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
 

## What I Learned

- How to clean and preprocess real-world data
- Visualizing missing values and handling them effectively
- Extracting and analyzing patterns with the help of visualizations
- Engineering new features (like `FamilySize`) to gain deeper insights
- Building a full EDA report from raw CSV to meaningful conclusions


## Sample Visualizations

- Missing data heatmap
- Survival count plot
- Survival by gender & class
- Age & fare distributions
- Correlation heatmap
- Family size survival plot
