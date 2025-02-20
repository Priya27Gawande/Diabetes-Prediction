# Diabetes Prediction

## Project Overview

This project focuses on predicting the presence or absence of diabetes using a healthcare diabetes dataset. It includes exploratory data analysis, data visualization, outlier detection, data preprocessing, and the implementation of various machine learning models to determine the best classifier for diabetes prediction.

## Dataset

The dataset consists of 2768 rows and 10 columns, with 8 independent features and 1 dependent feature (Outcome). The Outcome column represents whether an individual has diabetes (1) or not (0). The dataset is preprocessed to remove any anomalies and outliers before model training.

## Technologies Used

Python

Pandas

NumPy

Seaborn

Matplotlib


## Steps Followed

1. Data Preprocessing

     Loaded the dataset using Pandas.

     Checked for missing values and duplicates.

     Removed irrelevant columns.

     Handled outliers using quantile clipping.

2. Exploratory Data Analysis (EDA)

     Used describe() and info() methods to understand data distribution.

## Created visualizations:

    Pair plots for relationship analysis.

    Pie chart for class distribution.

    Scatter plots to explore relations between key features.

    Correlation matrix heatmap.

    Histograms for variable distribution.

    Box plots to detect outliers.

## Installation & Usage

## Prerequisites

Ensure you have the following dependencies installed:

   pip install pandas numpy seaborn matplotlib scikit-learn mlxtend

   Running the Project

## Clone the repository:

   git clone https://github.com/your-repo/diabetes-prediction.git 
   cd diabetes-prediction

## Run the Python script:

python diabetes_prediction.py

