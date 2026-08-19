# Titanic Exploratory Data Analysis

A short exploratory data analysis of the classic Titanic dataset.

## Objective

The goal of this project is to understand which passenger characteristics were associated with survival. This is an EDA-only project; no machine-learning models are used.

## What I did

- Loaded the Titanic dataset using a relative path.
- Inspected the dataset structure, data types, summary statistics, and missing values.
- Handled missing `Age` values using the median.
- Filled the two missing `Embarked` values using the mode.
- Kept the sparse `Cabin` data rather than inventing missing values, while creating a `HasCabin` indicator.
- Compared survival rates by sex and passenger class.
- Examined the interaction between sex and passenger class.
- Explored age and fare distributions by survival outcome.
- Summarised the main findings and identified next steps.

## Key finding

Survival was strongly associated with sex and passenger class. Women had substantially higher survival rates than men, while first-class passengers generally had better survival outcomes than second- and third-class passengers. The combination of sex and class provides a clearer picture than either variable alone.

## How to run

Install the dependencies:

```bash
pip install -r requirements.txt