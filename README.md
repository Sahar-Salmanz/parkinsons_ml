# Parkinson's Disease Detection
A machine learning project using the UCI Parkinson's Disease dataset to analyze and classify Parkinson's disease from biomedical voice measurements.

## Overview
This project explores the UCI Parkinson's dataset (ID: 174), which contains a range of biomedical voice measurements from people with and without Parkinson's disease. The goal is to distinguish healthy individuals from those with Parkinson's based on vocal features.

## Dataset Features
The dataset includes the following vocal measurements:


|Feature|Description|
|-------|-----------|
|MDVP:Fo(Hz)|Average vocal fundamental frequency|
|MDVP:Fhi(Hz)|Maximum vocal fundamental frequency|
|MDVP:Flo(Hz)|Minimum vocal fundamental frequency|
|MDVP:Jitter|Variation in fundamental frequency|
|MDVP:Shimmer|Variation in amplitude|
|NHR, HNR|Noise-to-harmonics ratio measures|
|RPDE, D2|Nonlinear dynamical complexity measures|
|DFA|Signal fractal scaling exponent|
|spread1, spread2, PPE|Nonlinear measures of fundamental frequency variation|
|status|Target – 1 = Parkinson's, 0 = Healthy|


## Installation
__Prerequisites__

- Python 3.8+
- pip

__Requirements__

- ucimlrepo
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
