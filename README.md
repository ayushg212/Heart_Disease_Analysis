# Heart Disease Exploratory Data Analysis

This repository contains a Jupyter Notebook for Exploratory Data Analysis (EDA) on a heart disease dataset. The purpose of this analysis is to explore the dataset, understand its structure, and identify key insights that could help in predicting heart disease.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Notebook Contents](#notebook-contents)
- [Results](#results)

## Overview

Heart disease is a leading cause of death globally. By analyzing the patterns and correlations within medical data, we can identify important factors that contribute to heart disease. This notebook provides a thorough analysis of the given heart disease dataset, aiming to uncover insights that could potentially aid in early detection and prevention.

## Dataset
The data sample is very informative and is represented by 319 thousand patients on 18 criteria.
The dataset used in this analysis contains following features:
* HeartDisease - target trait.
* BMI - a value that allows you to assess the degree of correspondence between a person's mass and his height, and thereby indirectly judge whether the mass is insufficient, normal or excessive. It is important in determining the indications for the need for treatment.
* Smoking is a major risk factor for cardiovascular disease. When smoke from a cigarette is inhaled, the reaction of the cardiovascular system immediately follows: within one minute, the heart rate begins to rise, increasing by 30% within ten minutes of smoking. The bad habit also increases blood pressure, fibrinogen and platelet levels, making blood clots more likely.
* AlcoholDrinking - alcohol causes not only temporary disturbances in the functioning of the heart, but also permanent ones. Heart pain after alcohol is not the only health problem associated with alcohol consumption.
* Stroke - Ischemic stroke occurs 4 times more often than hemorrhagic. One of the leading causes of this suffering is heart disease, which impairs its functioning, as a result of which the blood flow in the arteries is disturbed and the blood supply to the brain is reduced. Another cause of stroke in heart disease is thromboembolism, when clots form in the cavities of the heart (most often with heart failure) - blood clots.
* PhysicalHealth - how many days in a month did you feel poor physical health.
* MentalHealth - how many days in a month did you feel poor mental health.
* DiffWalking - difficulty climbing stairs.
* Sex - gender of a person.
* AgeCategory - age category of the subjects.
*Race-obviously:)
* Diabetic - obviously :)
* PhysicalActivity - adults who reported doing physical activity or exercise during the past 30 days other than their regular job
* GenHealth - well-being.
* SleepTime - number of hours of sleep.
* Asthma- obviously :)
* KidneyDisease - obviously :)
* Skin Cancer - obviously :)

## Requirements

To run this notebook, you need to have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

You can install these libraries using pip:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Installation
Clone the repository:
```sh
git clone https://github.com/ayushg212/Heart_Disease_Analysis.git
```

## Navigate to the directory:
```sh
cd Heart_Disease_Analysis
```
### Usage
Launch Jupyter Notebook:
```sh
jupyter notebook
```
Open heart-disease-exploratory-data-analysis.ipynb and run the cells to perform the analysis.

## Notebook Contents

1. **Introduction**
   - Overview of the problem and objectives.

2. **Loading the Data**
   - Importing necessary libraries and loading the dataset.

3. **Data Cleaning and Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Data transformation

4. **Exploratory Data Analysis**
   - Univariate analysis
   - Bivariate analysis
   - Multivariate analysis
   - Visualization of key features and their relationships

5. **Feature Selection**
   - Identifying important features using statistical methods

6. **Modeling**
   - Basic predictive modeling to test the feasibility of the analysis

7. **Conclusions**
   - Summary of findings and potential next steps


## Results
The EDA revealed several important factors related to heart disease, such as age, sex, cholesterol levels, and more. These insights can be further used for building predictive models and improving healthcare strategies.

