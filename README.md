## Food Nutrition Analysis

## Project Overview

This repository documents an end-to-end Data Science project focused on understanding food nutrition data through a structured and transparent workflow. The goal of this project is to strengthen my data science skills by working on a real-world dataset from data exploration to insight generation and modeling while sharing the learning process openly.

This project is also part of my learning-in-public journey, where anyone interested can explore the notebooks and learn alongside me.

## Objectives

* Perform Exploratory Data Analysis (EDA) on real-world nutrition data
* Understand data structure, quality, and limitations
* Identify meaningful health-related signals from nutritional features
* Build a strong foundation for future feature engineering and modeling
* Practice professional, reproducible data science workflows using GitHub

## Repository Structure

food-nutrition-analysis/
-- data/
    ---Processed             # Cleaned dataset
    ---raw/                  # Raw nutrition dataset
-- notebooks/
    --- 01_data_understanding.ipynb
       # Initial EDA: structure, quality, and basic insights
-- README.md


## Dataset

* Source: OpenFoodFacts (cleaned subset)
* Type: Food nutrition data
* Features include:

  * Energy (kcal)
  * Sugar, fat, saturated fat
  * Fiber, protein, salt
  * Nutrition score (Nutri-Score)
  * Processing level (NOVA group)

The dataset is already partially cleaned, allowing the project to focus on analysis, interpretation, and decision-making, which closely reflects real-world industry workflows.

##  Current Progress

### Stage 1: Exploratory Data Analysis (Completed)

* Data ingestion and validation
* Dataset structure and feature inspection
* Data quality and missing-value analysis
* Statistical exploration of key nutritional variables
* Initial insight discovery (e.g., extreme sugar values)

### Stage 2: Data Cleaning & Validation (Completed)

* Handled missing values using appropriate strategies
* Removed invalid or inconsistent records
* Ensured correct data types across all features
* Validated cleaned dataset using summary statistics
* Saved final cleaned dataset to data/processed/cleaned_nutrition.csv following best practices

### Stage 3: Insight-Driven EDA (Completed)

* Explored deeper questions beyond basic EDA
* Investigated sugar vs fiber relationships and identified dataset limitations
* Recognized that the dataset mixes raw ingredients and packaged foods, which affects interpretation
* Shifted analysis to population-level comparisons using NOVA food processing groups

Found that:
Minimally processed foods tend to have much lower salt levels
Ultra-processed foods show lower average fiber
Sugar alone is not a reliable single indicator of nutrition quality

### Stage 4: Feature Engineering (Completed)

- Designed domain-informed features instead of relying only on raw nutrition values
- Created new features:
  - Sugar–Fiber Ratio
  - Protein Density
  - Salt Intensity
  - Ultra-Processed Flag (from NOVA group)
  - Nutrient Balance Score (composite indicator)
- Validated newly created features using descriptive statistics and visualization
- Observed that engineered features improve interpretability compared to individual nutrients
- Prepared final dataset for model-building phase

This stage strengthened understanding of how domain knowledge and thoughtful transformations can significantly improve data quality before applying machine learning models.

## Next Steps

* Basic machine learning models
* Clear documentation of findings and decisions

## Tools & Technologies

* Python
* Pandas
* GitHub Codespaces
* Jupyter Notebooks

## Learn Along

This repository is public and open. Feel free to:

* Explore the notebooks
* Follow the project’s progression
* Learn along as the analysis evolves

Feedback and discussions are always welcome.


This project emphasizes clarity, transparency, and strong analytical thinking over quick results or black-box models.
