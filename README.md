# IDAML 1: Income Groups (Project 1)

This repository holds the final project submission for the course "Intelligent Data Analysis and Machine Learning 1" offered during the SOSE23 at the Universität Potsdam.

## Problem Statement 
A polling institute conducted interviews with 30,000 individuals to gather personal data for the purpose of estimating their income, as stored in the file "[./einkommen.train](https://github.com/Nid989/IDAML23_PROJECT/blob/main/einkommen.train)". During this process, various statistical details were collected, encompassing both numerical and categorical features. However, for approximately 25,000 interviewees, the data related to their income is notably unknown. This project's objective is to analyze the provided data, select an appropriate data transformation algorithm, and determine how to handle missing values. Subsequently, a model will be trained using the chosen transformed attributes to predict whether a person's income falls into the <=50K or >=50K category. The learned model will then be applied to the 25,000 individuals whose income group is unknown.

## Project Directory Tree
```
├── configurations/
│   ├── config.yaml
│   ├── decision_tree_config.yaml
│   ├── bagging_decision_tree_config.yaml
│   ├── random_forest_config.yaml
│   ├── logistic_regression_config.yaml
│   └── neural_network_config.yaml
├── plots/
│   └── decision_tree.png
├── einkommen.train
└── data_exploration_and_models.ipynb
```
