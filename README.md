 Objective

To extract meaningful insights from the Titanic dataset using statistical and visual exploration techniques.


Tools Used :-

i)Python

ii)Pandas

iii)Matplotlib

iv)Seaborn

v)Jupyter Notebook


 Dataset

Source: Kaggle Titanic Dataset

Records: 891 rows, 12+ columns

Target Variable: Survived (1 = survived, 0 = not survived)



 Tasks Performed

1. Data Loading 

Loaded Titanic dataset using Pandas.

Checked for missing values using .info().

Dropped/handled missing values in Age, Embarked, and Cabin.


2. Statistical Summary

Used .describe() and .value_counts() to understand distribution.

Identified:

Mean age ~29.7 years.

~38% passengers survived.



3. Visual Exploration

Pairplot to explore relationships between features.

Heatmap to analyze correlations.

Histograms for age distribution.

Boxplots to compare survival by age and class.

Scatterplots for Fare vs Age colored by survival.


4. Observations

Females had higher survival rates.

1st class passengers more likely to survive.

Higher fare → higher survival.

Younger passengers had better chances.


 Summary of Findings :-

Factor	Impact on Survival

Sex	Females had higher survival rates
Pclass	Higher class → higher survival
Fare	Positively correlated with survival
Age	Survivors tended to be younger

Deliverables :-

titanic_analysis.ipynb: Jupyter notebook with step-by-step analysis

titanic_report.pdf: PDF report summarizing insights

README.md: Summary of the project and findings
