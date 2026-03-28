# Titanic EDA

Exploratory Data Analysis on the Titanic dataset from Kaggle.

## What I did
- Handled missing values (Age: group median, Cabin: binary feature, Embarked: mode)
- Performed univariate and bivariate survival analysis
- Encoded categorical features (Label Encoding, One-Hot Encoding)
- Created FamilySize feature from SibSp and Parch
- Built correlation heatmap to identify top predictors

## Key Findings
- Female survival rate: 74% vs male: 19%
- 1st class survival: 63% vs 3rd class: 24%
- Top 3 features for ML: Sex, Pclass, Fare
- Solo travelers had lowest survival rate (30%)

## Tools
Python, Pandas, Matplotlib, Seaborn