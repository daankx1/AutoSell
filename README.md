# AutoSell - A Platform for Selling Your Used Car

## Overview

This repository contains a Jupyter notebook for preprocessing, exploring a dataset of used cars, analyzing correlations, and building predictive models using various machine learning techniques including classification, clustering, regression, and neural networks.

## Dataset

The dataset used in this notebook is `used_cars.csv`, which contains information about cars that customers have sold or are trying to sell via AutoSell in 2023. 

## Table of Contents

1. **AutoSell - A Platform for Selling Your Used Car**
2. **Preprocessing the Dataset**
   - Create a dataframe from `used_cars.csv`.
   - Identify columns with NaN values.
   - Display rows containing NaN values.
   - Handle NaN values in `clean_title`, `accident`, and `fuel_type` columns.
   - Remove invalid entries in the `fuel_type` column.

3. **Exploring the Dataset**
   - Exploration of Target Feature
     - Boxplot and histogram analysis for the `price` column.
   - Exploration of Correlations
     - Correlation matrix for numerical attributes.
     - Univariate and multivariate correlations with categorical attributes using boxplots.

4. **Predicting Prices**
   - Baseline Model
     - Using the average price of all cars.
   - Prediction by Classification
     - Price binning, data transformation, model training, and price prediction.
   - Prediction by Clustering
     - Data transformation, computing distance matrix, applying DBSCAN, and price prediction.
   - Prediction by Regression and Neural Networks
     - Feature engineering, selection, data transformation, model training, linear regression, non-linear kernels, and neural networks.
   - Discussion

5. **Predicting Time-to-Sale**
   - Data preparation, target feature creation, sensitivity and specificity, data transformation for classification.
   - Model training and evaluation.
   - Discussion

## Instructions

1. Clone the repository:
    ```sh
    git clone https://github.com/daankx1/AutoSell.git
    ```
2. Navigate to the directory:
    ```sh
    cd AutoSell
    ```
3. Open the `final.ipynb` notebook using Jupyter Notebook or Jupyter Lab:
    ```sh
    jupyter notebook final.ipynb
    ```

## Dependencies

The notebook requires the following Python libraries:
- numpy
- pandas
- seaborn
- matplotlib

You can install these dependencies using pip:
```sh
pip install numpy pandas seaborn matplotlib
