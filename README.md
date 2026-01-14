# Titanic-EDA
Exploratory Data Analysis on Titanic dataset using Python

🚢 Titanic Survival Analysis – Exploratory Data Analysis (EDA)
📌 Project Overview

This project performs end-to-end Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors that influenced passenger survival during the disaster.

The analysis includes:

Data cleaning and preprocessing

Feature engineering

Statistical insights using NumPy

Advanced visualizations using Matplotlib, Seaborn, and Plotly

Actionable analytical insights

🧰 Tech Stack

Python

NumPy – statistical analysis

Pandas – data manipulation & cleaning

Matplotlib – basic visualizations

Seaborn – statistical plots

Plotly – interactive visualizations

📂 Dataset

Source: Kaggle – Titanic: Machine Learning from Disaster

File Used: train.csv

🔄 Project Workflow
1️⃣ Data Loading

Loaded dataset using Pandas

Inspected shape, data types, and basic statistics

2️⃣ Data Cleaning

Handled missing values:

Age → filled with mean

Embarked → filled with mode

Dropped high-missing column (Cabin)

Removed duplicate records

Corrected data types for categorical features

3️⃣ Feature Engineering

Created new meaningful features:

FamilySize = SibSp + Parch + 1

IsAlone (binary feature)

Title extracted from passenger names

AgeGroup (Child, Teen, Adult, MiddleAge, Senior)

FarePerPerson

4️⃣ Exploratory Data Analysis (EDA)

Performed univariate and multivariate analysis:

Survival distribution

Survival by gender

Survival by passenger class

Age and fare distribution

Family size impact on survival

Correlation heatmap

5️⃣ Statistical Insights (NumPy)

Mean, median, standard deviation of Age and Fare

Overall survival rate

Survival rate by:

Gender

Passenger class

6️⃣ Advanced Visualizations

Survival rate by age group

Survival vs family size trend

Interactive Plotly charts:

Class vs gender vs survival

Multi-level survival breakdown

📊 Key Insights

Gender was the strongest predictor of survival
→ Female passengers had a significantly higher survival rate

Passenger class influenced survival chances
→ First-class passengers survived more than third-class passengers

Children were prioritized
→ Higher survival rate among younger age groups

Family size mattered
→ Small families survived more than solo or very large families

Fare indirectly impacted survival
→ Higher fare correlated with higher passenger class and better survival

🧠 Conclusion

The analysis demonstrates that demographic and socio-economic factors played a major role in survival outcomes. Proper feature engineering and EDA revealed hidden patterns that are not directly visible in raw data.
