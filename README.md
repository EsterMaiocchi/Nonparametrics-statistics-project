# Nonparametric Analysis of Feature-Driven Performance in Wearable Health Devices

## Overview
This project was developed as part of a university course in Nonparametric Statistics.  
It explores the relationship between technical features, price, and user satisfaction in the wearable health device market using nonparametric and distribution-free methods.

## Objective
The goal of the analysis is to support data-driven decision-making from a customer perspective by addressing three main questions:
- Which device category offers the best balance between accuracy, battery life, and features?
- Is a higher price justified by better performance or mainly driven by brand value?
- Can we predict user satisfaction for a new device?

## Dataset
The analysis is based on a dataset of 2000+ wearable devices collected from Kaggle, including:
- Technical features (battery life, sensors, accuracy metrics)
- Market variables (price, brand, category)
- User-related outcomes (satisfaction ratings)

## Methods
The project applies a range of advanced statistical techniques, including:
- Nonparametric ranking and permutation-based ANOVA
- Wilcoxon tests and permutation-based chi-square tests
- Construction of composite performance indices
- Generalized Additive Models (GAM)
- Quantile regression
- Conformal prediction (standard and normalized)

## Key Results
- Smartwatches provide the best overall balance between performance, features, and usability.
- Price is only partially explained by technical performance and is strongly influenced by brand effects.
- User satisfaction can be effectively predicted using price and device category, with uncertainty quantified through conformal prediction.

## Tools
- R
- Statistical modeling and data analysis techniques

## Project Structure
- `report.pdf`: full analysis and results
- `code/`: scripts used for data preprocessing and analysis (if included)

## Authors
- Ester Maiocchi, Marianna Mazza, Arianna Perotti 
