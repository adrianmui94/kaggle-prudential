# Kaggle Prudential Project

## Introduction

From https://www.kaggle.com/c/prudential-life-insurance-assessment

In 2015, Prudential proposed a challenge to Kaggle data scientists to see if Machine Learning algorithms could help customers in shopping for life insurance. The idea would be that having pretrained algorithms on the website to recommend plans would dramatically speed up the process and reduce the amount of potential customers from losing interest, as the life insurance application process in their words is "antiquated".

## Prudential Life Insurance Prediction - EDA 

This preliminary EDA was done to examine how variant the data was across each of the different features and see if there were any clear trends which could be used in feature engineering. The feature columns themselves are undescriptive and can only be judged by their content and variability. 

The heavy class imbalance is acknowledged and we address the possibility of simply developing an algorithm that predicts whether or not the proposed user would belong to the majority class.

## Prudential Life Insurance Engineering

This notebook expands upon the previous idea and visualizes the majority class versus others again. 

We create 8 basic one versus all classifiers and plot SHAP / feature importances to help us understand what each may be the most important features for that class. We then use these results to develop additional features.

## Prudential Life Insurance - ML Final 

This notebook creates our proposed stacked model and uses a final neural network at the end to aggregate the results.

