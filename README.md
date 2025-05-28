# EL-Internship-Task-2

# Titanic Dataset - Exploratory Data Analysis (EDA)

## Objective
To understand the Titanic dataset using Exploratory Data Analysis techniques by visualizing data and extracting meaningful insights that can guide future predictive modeling.

##  Tools Used
- [Google Colab](https://colab.research.google.com/drive/1QtmqWdoyfxQFFEd78iVQCa1vmqfdDCQI?usp=sharing)
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly (optional for interactivity)

## Dataset
- **Source:** [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **Filename:** `Titanic-Dataset.csv`

## EDA Workflow

### 1. Data Overview
- Checked dataset shape, column types, and basic structure using `info()` and `head()`.
- Descriptive statistics were generated with `describe()`.

### 2. Handling Missing Values
- Identified columns with missing data (e.g., `Age`, `Cabin`, `Embarked`).
- Noted the percentage of missing data for decision-making.

### 3. Univariate Analysis
- Used histograms and boxplots to explore:
  - Age distribution
  - Fare distribution
  - Outliers
  - Skewness

### 4. Bivariate Analysis
- Analyzed relationships between:
  - Sex vs Survived
  - Pclass vs Survived
  - Age vs Survived
  - Fare vs Survived

### 5. Correlation
- Heatmap created to visualize correlations among numerical variables.

## Key Insights

- **Survival Rate by Gender:** Females had a much higher survival rate than males.
- **Survival Rate by Class:** Passengers in 1st class were more likely to survive.
- **Fare Distribution:** Highly skewed with outliers among upper-class passengers.
- **Age Factor:** Younger passengers had slightly better chances of survival.
- **Family Size Impact:** Small families had better odds of survival than large ones.

## What I Learned
- Data cleaning and feature understanding are key to successful analysis.
- Visualization helps uncover non-obvious trends and patterns.
- EDA is a critical step before modeling to guide data preprocessing.

## Files Included
- `EDA_Titanic.ipynb` – Jupyter Notebook containing code and visualizations
- `Titanic-Dataset.csv` – Dataset used
- `README.md` – This file

## Author 
**NAME**: Dhanush  
**G-MAIL**: dhanushg0710@gmail.com
