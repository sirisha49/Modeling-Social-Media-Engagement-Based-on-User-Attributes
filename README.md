# Modeling-Social-Media-Engagement-Based-on-User-Attributes
This project combines exploratory data analysis and regression modeling to understand behavioral and demographic patterns in social media usage. In addition to uncovering trends through visualization and grouping, it applies linear regression to predict user engagement (time spent) based on variables such as age, income, and interest categories.

## Dataset Overview

The dataset used in this project is named `Social Media Analytics.xls` and contains user-level social media data including:

- **Demographics**: `Age`, `Gender`, `Location`, `Income`, `Profession`
- **Behavioral**: `Time_Spent`, `Platform`
- **Psychographics**: `Interests`, such as `Sports`, `Travel`, `Lifestyle`, etc.

The data includes a mix of numerical and categorical variables with intentional imperfections to simulate real-world datasets.

---

## Research Objectives

The project is guided by the following core research questions:

1. What is the average time spent on social media across all users?
2. Which platform has the highest user engagement?
3. How do interests and demographics (like age, gender, income) influence time spent on social media?
4. Can we predict time spent based on user attributes using regression analysis?

---

## Hypotheses

- Users aged 18–30 are expected to spend more time on Instagram than Facebook.
- Users with `Travel` or `Lifestyle` interests may show higher average engagement time.
- Higher income groups may spend less time on social platforms.
- There is a statistically significant relationship between user interests and time spent.

---

## Methodology

The project follows a structured analytical workflow:

- **Data Loading**: Load and inspect the Excel dataset using `pandas`
- **Data Cleaning**:
  - Standardize inconsistent values (e.g., spelling errors in interests)
  - Handle missing or malformed data entries
- **Descriptive Statistics**:
  - Compute mean, median, mode, and frequency distributions
- **Visualizations**:
  - Histograms, bar plots, pie charts, boxplots for behavioral patterns
  - Visual grouping by gender, platform, interest, and income
- **Hypothesis Testing**:
  - T-tests to compare means between groups (e.g., gender, platform usage)
  - ANOVA to test differences in time spent across income brackets
- **Regression Modeling**:
  - Linear regression using predictors like Age, Income, Interest to predict `Time_Spent`
  - Evaluated using R² score and residual plots

---

## Key Findings

- **Instagram** showed significantly higher usage among users aged 18–25.
- **Facebook** engagement skewed toward older age groups.
- Users with **Lifestyle** and **Travel** interests had higher time-on-platform averages.
- Higher income groups tended to spend slightly less time on social media.
- Regression analysis showed that Age, Interests, and Income were moderate predictors of engagement time.

---

## Technologies Used

- Python 3.x
- Jupyter Notebook
- `pandas`, `numpy`
- `matplotlib`, `seaborn` for data visualization
- `scipy.stats` for hypothesis testing
- `sklearn.linear_model` for regression modeling
- `openpyxl` for reading Excel files

---

## What I Learned

- Structured approach to EDA and behavioral pattern analysis
- Cleaning, encoding, and preparing mixed-type datasets for statistical modeling
- Running and interpreting statistical tests (t-tests, ANOVA)
- Building and evaluating linear regression models in Python
- How to effectively communicate data-driven insights visually and narratively

