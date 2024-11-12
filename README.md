**Titanic Data Analysis 🛳️**

*About*
This project aims to perform data cleaning and exploratory data analysis (EDA) on the famous Titanic dataset. Using Python and popular data analysis libraries, the analysis dives into key insights about survival rates, exploring relationships among variables like age, gender, and class to uncover patterns and trends.

*Dataset*
The dataset used in this project is the Titanic dataset, available on Kaggle. It contains data on passengers of the Titanic, including attributes like:

Survived: Survival indicator (0 = No, 1 = Yes)
Pclass: Passenger class (1 = First, 2 = Second, 3 = Third)
Sex: Gender of the passenger
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Fare: Ticket fare paid by the passenger
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

*Analysis Workflow*
1. Data Cleaning
Handled missing values in Age by filling them with the average age of passengers.
Dropped irrelevant columns, such as Ticket and Cabin, to streamline the analysis.
2. Exploratory Data Analysis (EDA)
Key analyses conducted include:

*Age Distribution*: Visualized age distribution using a histogram to understand passenger demographics.
*Survival by Gender*: Calculated and visualized survival rates by gender, showing that females had higher survival rates.
*Survival by Passenger Class*: Created a plot to show the survival rate across different classes.
*Port of Embarkation*: Explored survival rates by embarkation port.
*Correlation Analysis*: Used a heatmap to display correlations among numerical variables, helping to identify significant relationships.

*3. Visualizations*
Several visualizations were created to illustrate findings, including:

Age Distribution Histogram
Survival Rate by Gender and Class
Correlation Heatmap
Pairplot for Age, Fare, and Pclass colored by Survival
Libraries Used
pandas for data manipulation
matplotlib and seaborn for data visualization

*Key Findings*
Gender and Survival: Women had a significantly higher survival rate than men.
Class and Survival: First-class passengers were more likely to survive compared to second and third-class passengers.
Age and Fare Correlations: Younger passengers and those who paid higher fares had a slight survival advantage.

*Acknowledgements*
Titanic Dataset: Kaggle
