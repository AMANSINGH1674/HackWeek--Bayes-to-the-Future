# Bayes to the Future: Predicting Heart Disease with Data

## Overview

This project models and predicts heart disease risks using a Bayesian Network built from patient data. We preprocess the data, normalize numerical values, categorize relevant features, and build a probabilistic graphical model using `pgmpy`.

## Features

- Clean and normalize health data
- Bayesian Network based on structure: `age → fbs → target → (chol, thalach)`
- Maximum Likelihood Estimation for learning
- Inference using variable elimination
- Graphical output of Bayesian structure

## Setup
pip install pandas matplotlib networkx pgmpy
else
Upload ipynb and csv files on Google Collab and run the script
