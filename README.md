# TripAdvisor Hotel Review Analysis

## Overview
This project undertakes a detailed machine learning analysis of TripAdvisor hotel reviews, aiming to provide actionable insights for business intelligence applications. Utilizing the Weka machine learning toolkit, along with supplementary data processing in R and Python, this analysis addresses two critical scenarios:
1. Predicting hotel ratings based on review texts.
2. Determining the influence level of review authors.

## Table of Contents
- [Project Description](#project-description)
- [Data Processing](#data-processing)
- [Scenario Analyses](#scenario-analyses)
  - [Scenario 1: Hotel Rating Prediction](#scenario-1-hotel-rating-prediction)
  - [Scenario 3: Author Influence Modeling](#scenario-3-author-influence-modeling)
- [Conclusions and Recommendations](#conclusions-and-recommendations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description
The analysis delves into a subset of a large TripAdvisor review dataset, focusing on 3,118 reviews with 22 attributes. The project's aim is to extract business intelligence through the application of machine learning models to:
- Predict overall hotel ratings from review texts.
- Assess the influence of review authors based on their travel history and review engagement.

## Data Processing
Data preprocessing steps included text mining techniques for review texts, filling missing values, binary conversion of categorical variables, and feature engineering for improved model performance. Notable techniques included web scraping to determine author locations and SMOTE for addressing data imbalance.

## Scenario Analyses
### Scenario 1: Hotel Rating Prediction
This scenario focused on predicting hotel ratings using review texts, employing several machine learning models to find the one best suited for accurate sentiment prediction. The Support Vector Machine with Logistic and PolyKernel (SMO) model demonstrated the highest predictive accuracy, achieving an 81.8% accuracy rate.

### Scenario 3: Author Influence Modeling
The analysis aimed to predict whether a review author is an influential traveler, defined as having visited more than 15 cities. The Random Forest model was selected for its superior performance, achieving a 94% accuracy rate in identifying such authors.

## Conclusions and Recommendations
The study concludes that machine learning models, particularly SMO for scenario 1 and Random Forest for scenario 3, can significantly aid in understanding customer sentiments and the influence of review authors. These insights can inform marketing strategies, customer segmentation, and competitive analysis.
