
🧠 Stroke Data Analysis & Risk Insights
Analysis of medical and lifestyle data to understand the key factors associated with stroke risk.

📌 Project Overview
This project explores a medical dataset related to stroke occurrence, aiming to identify patterns and risk factors using Python.
The analysis covers demographics, medical conditions, glucose levels, BMI, lifestyle habits, and work type.
The main goal is to answer key analytical questions such as:

Do males or females experience more strokes?
Which age groups have the highest stroke risk?
Is hypertension strongly associated with strokes?
Do individuals with heart disease show higher stroke likelihood?
Could marital status be a contributing factor?
Are people working stressful private jobs more likely to have strokes?
Do individuals in urban areas face higher stroke risk?
How important is glucose level in stroke prediction?
How does BMI relate to stroke across age and gender?
Does smoking significantly increase stroke risk?


📊 Steps Performed in the Notebook
1. Loading & Inspecting the Dataset

Imported Pandas, NumPy, Seaborn, Matplotlib
Loaded the stroke dataset
Displayed the first rows, shape, and summary

2. Descriptive Analytics

Statistical summary for key variables
Observations on:

Age distribution
Glucose levels
BMI spread
Hypertension & heart disease counts



3. Handling Missing Values

Imputed BMI missing values
Checked for categorical missing entries
Cleaned dataset for analysis

4. Univariate Analysis

Distribution of age, glucose level, and BMI
Countplots for:

Gender
Work type
Smoking status
Residence type



5. Bivariate Analysis

Relationship between stroke and:

Age
BMI
Glucose levels
Heart disease
Hypertension
Work type
Smoking status
Residence type


Scatterplots, boxplots, histograms

6. Correlation Heatmaps

No strong numerical correlations
Moderate connections between age, glucose, and BMI

7. Feature Preprocessing

Encoding categorical features
Scaling numerical variables
Splitting into training and test sets

8. Modeling
Example models:

Logistic Regression
Random Forest
Decision Tree
XGBoost


🧠 Key Insights From the Analysis

Age strongly affects stroke likelihood — older age groups show significantly higher risk.
Hypertension and heart disease are major contributing medical conditions.
People with very high glucose levels are more likely to have strokes.
BMI interaction with age and gender needs observation—certain groups are more vulnerable.
Private job workers show higher counts, possibly due to stress.
Urban residents show slightly higher stroke counts but needs deeper confirmation.
Smokers display higher stroke frequency compared to non‑smokers.
No strong correlation among numerical variables alone—risk is multi-factorial.


🛠 Tools & Libraries

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit‑learn


📑 Files
notebooks/
│── stroke_analysis.ipynb
data/
│── stroke_data.csv
README.md


🎯 Project Purpose
The project aims to understand the risk factors associated with stroke and demonstrate the use of data analysis, EDA, visualization, and machine learning techniques applied to a real-world medical dataset.

🤝 Acknowledgments
This work was completed as part of my hands‑on learning in Data Analysis, exploring real healthcare data and building actionable insights.
