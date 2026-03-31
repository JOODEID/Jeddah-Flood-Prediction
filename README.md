# Jeddah-Flood-Prediction

## Authors

Joud Alharbi  
KFUPM – College of Design and Built Environment  
Sadam Al Azani
KFUPM - SDAIA-KFUPM joint Reserch Center for Artificial Intelligence

## Research Topic:  
AI-Driven Digital Twin for Flood Risk Prediction and Stormwater Management in Jeddah

This repository contains the implementation of a machine learning–based flood risk prediction model integrated with a Dynamic Digital Twin prototype for stormwater management in Jeddah, Saudi Arabia.
The study proposes an AI-driven framework that transforms flood risk predictions into a dynamic system state representation to support scenario-based analysis and decision support for urban flood management.

## Dataset

The dataset includes meteorological variables used for flood-risk classification:
- Rainfall (RR)
- Temperature (TE)
- Humidity (HU)
- Wind Speed (WS)
- Month (MO) 
The dataset contains 3652 observations used for model training and evaluation.

## Machine Learning Models

Several classification models were evaluated:
- Random Forest
- XGBoost
- Gradient Boosting (Selected Model)

Model performance was evaluated using:
- Accuracy
- Macro-averaged F1 score
- Confusion Matrix
- ROC Curve
- Learning Curve

## Digital Twin Component

The Digital Twin prototype converts AI model outputs into a structured system state representation using a dynamic dataframe.
This representation enables:
- Continuous flood-risk monitoring
- Scenario-based rainfall simulations
- Integration with spatial visualization platforms (GIS)
