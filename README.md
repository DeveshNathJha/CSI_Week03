# CSI_Week03
Titanic Dataset EDA using Matplotlib | Week 3 Internship Assignment @ Celebal Technologies

This assignment explores the **Titanic dataset** to understand the survival patterns of passengers based on factors like gender, age, ticket class, fare, and embarkation point.

The analysis involves:
- Data Cleaning and Handling Missing Values
- Univariate and Bivariate Data Visualization
- Visual Analysis using Matplotlib
- Summary and Observations based on graphs

> This assignment was part of my internship at Celebal Technologies, Week 3 – with the goal of practicing data visualization and analytical storytelling.

## Dataset Info
- **Source:** [Titanic Dataset on GitHub](https://raw.githubusercontent.com/pandas-dev/pandas/master/doc/data/titanic.csv)
- **Rows:** 891
- **Columns:** 15
- **Target Variable:** `survived` (0 = No, 1 = Yes)

###  Key Features Used:
- `pclass` – Passenger Class (1st, 2nd, 3rd)
- `sex` – Gender
- `age` – Age
- `sibsp` – Siblings/Spouse aboard
- `parch` – Parents/Children aboard
- `fare` – Ticket Fare
- `embarked` – Port of Embarkation


##  Visualizations Included
- Bar Charts (Survival Count, Passenger Class, Gender)
- Histograms (Age, Fare)
- Pie Charts (Embarkation Point)
- Line Graph (Custom Fare Trend by Class – for assignment variety)
- Scatter Plot (Fare vs Age)
- Correlation Heatmap (Numeric Feature Analysis)

> The visualizations were implemented using **Matplotlib** to meet coursework requirements without using Seaborn.

##  Key Insights
- Females had a significantly higher survival rate than males.
- Passengers in 1st class had better survival chances.
- Children were more likely to survive compared to adults or seniors.
- Passengers who embarked from Cherbourg had the highest survival ratio.
- Higher fare tickets were generally associated with higher survival.


## Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (for missing value imputation using IterativeImputer)


