# NFL Combine & Draft Impact: Which Wide Receivers Will Succeed? 

## Project Overview

The goal of this project is to analyze whether athletic performance in the NFL Combine and draft position are strong predictors of success in the NFL. Using fantasy football points as a proxy for success, we explore relationships between combine metrics, draft rounds, and player performance over multiple seasons.

## Datasets

### Kaggle Datasets:

  * NFL Player Statistics Dataset (2004-Present)

  * NFL Stats 1999-2022

## Data Pipeline

### 1. Data Collection: 
  * We aggregate multiple datasets containing NFL Combine results, draft rounds, and yearly player performance statistics.

### 2. Data Cleaning & Preprocessing:

  * Filtered for Wide Receivers (WRs)

  * Merged datasets on player ID
    
  * Filter for rookie season

  * Imputed missing values using median imputation

### 3. Feature Engineering:

  * Created new metrics for performance evaluation
  
  * Applied dimensionality reduction techniques (PCA)

### 4. Modeling Approaches:
   
  * Baseline: Multiple Linear Regression
          
  * Advanced: Random Forest, XGBoost, LightGBM, Neural Networks
          
  * Model evaluation based on R-squared, RMSE, and feature importance
              

## Exploratory Data Analysis (EDA)

We conducted various analyses including:

  * Histograms & Boxplots: Examined distributions of combine metrics
    
  * Correlation Heatmaps: Identified relationships between combine stats and performance metrics
    
  * Scatter Plots: Explored relationships between draft rounds and success metrics

## Results Summary

  * Players drafted earlier in the draft tend to have higher fantasy point averages.
  
  * Combine metrics such as 40-yard dash and broad jump show weak correlations with long-term success.
  
  * Bench press strength has minimal impact on receptions or receiving yards.
  
  * Machine learning models (Random Forest, XGBoost) outperform linear regression in predicting performance.

## Authors

  * Praveen Manimaran
  * Vitush Agarwal
  * William Guy
