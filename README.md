# Cardiovascular Disease Analysis

Exploratory data analysis of 70,000 patient records to understand which factors are linked to cardiovascular disease.

**Workflow:** Data Cleaning → Feature Engineering → Exploratory Data Analysis

## Dataset
70,000 patient records with age, gender, height, weight, blood pressure, cholesterol, glucose, smoking, alcohol, physical activity, and a target column (`cardio`) showing the presence of cardiovascular disease.

## What I Did
**1. Data cleaning**
- Converted age from days to years
- Converted coded values (cholesterol, glucose, smoking, alcohol, activity, gender) to readable labels
- Removed impossible blood pressure, height, weight and BMI values

**2. Feature engineering**
- BMI and BMI category
- Age groups
- Pulse pressure (systolic − diastolic)
- Blood pressure category

**3. Exploratory analysis**
- Class balance of the target
- Disease rate by age group, gender, BMI category and blood pressure category
- Disease rate by cholesterol and glucose level
- Disease rate by smoking, alcohol and physical activity

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## How to Run
```bash
git clone 
cd cardiovascular-disease-eda
pip install numpy pandas matplotlib seaborn jupyter
jupyter notebook Project_Cardio.ipynb
```

## By: Mustafa Abbas Ali
