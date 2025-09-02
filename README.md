# Mental Health Classification Project

This repository contains an exploratory data analysis and machine learning project focused on mental health classification, specifically depression prediction, based on the Kaggle competition "Playground Series - Season 4, Episode 11".

## Dataset Overview

The dataset contains information on various factors potentially related to depression, including:

- **Demographics**: Age, Gender, City
- **Education/Occupation**: Working Professional or Student status, Profession, Degree
- **Stressors**: Academic Pressure, Work Pressure, Financial Stress
- **Well-being Indicators**: Study Satisfaction, Job Satisfaction, Financial Well-being
- **Clinical Risk Factors**: Depression (target variable), Suicidal thoughts, Family History of Mental Illness
- **Performance Metrics**: CGPA, Work/Study Hours
- **Lifestyle Factors**: Sleep Duration, Dietary Habits

## Notebooks

### 1. Exploratory Data Analysis (`explore_mental_data.ipynb`)

This notebook provides a comprehensive exploration of the mental health dataset, including:

- Basic data inspection and preprocessing
- Target variable distribution analysis (Depression)
- Correlation analysis between depression and numerical features
- Chi-square analysis for categorical variables and depression
- In-depth analysis of specific factors:
  - Occupation and education status effects on depression
  - Relationship between suicidal thoughts and depression
  - Education level and depression rates
  - Lifestyle factors (diet, sleep) and depression
  - Geographic variation in depression rates
  - Gender differences in depression
  - Age distribution analysis

Key findings include:
- Strong negative correlation between age and depression (-0.56)
- Strong positive correlation between academic pressure and depression (0.48)
- Significant relationships between all categorical variables and depression
- Education level, occupation status, and suicidal thoughts show the strongest associations with depression

### 2. Model Training (`model_training.ipynb`)

This notebook focuses on building and evaluating machine learning models to predict depression based on the features in the dataset.

## Competition Information

This project is based on the Kaggle competition "Playground Series - Season 4, Episode 11" which focuses on mental health classification. The goal is to predict depression status based on various demographic, lifestyle, and psychological factors.

## Getting Started

To run the notebooks:

1. Clone this repository
2. Ensure you have Python and Jupyter installed
3. Install the required dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
4. Open the notebooks in Jupyter Notebook or JupyterLab:
   ```
   jupyter notebook
   ```
   or
   ```
   jupyter lab
   ```

## Acknowledgements

- Kaggle for providing the dataset and competition framework
- [Include any other acknowledgements here]
