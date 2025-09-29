# Internship-Assignments-DA-day5
This repository contains my daily internship assignments and projects.
# Titanic Dataset - EDA Report

## Dataset Overview
- Columns: PassengerId, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked
- Missing Values:
  - Age: ~20%
  - Cabin: many missing
  - Embarked: very few missing

## Key Findings
1. Age: Most passengers between 20-40 years.
2. Fare: Right-skewed distribution, few very high outliers.
3. Sex: Clear survival advantage for females (if Survived column present).
4. Pclass: Higher class → higher fares, higher survival chances.
5. Embarked: Majority embarked from 'S'.

## Recommendations
- Impute Age (median or model-based).
- Encode categorical variables (Sex, Embarked).
- Consider new features like FamilySize, HasCabin.

