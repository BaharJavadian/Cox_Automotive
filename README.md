# Cox_Automotive: Semi-Supervised Learning to Identify Risky Dealers

This project aims to uncover patterns in dealership behavior related to **vehicle guarantees and returns**, using both labeled and unlabeled data. Given the scarcity of labeled examples (~7% of vehicles), I used a **semi-supervised learning** approach to extract meaningful insights.

## Problem Statement

DealShield, a Cox Automotive business unit, provides return guarantees on vehicles. However, only a small portion of vehicles in the dataset include return or guarantee labels. The challenge is to use the labeled and unlabeled data together to **identify risk-prone dealers**, helping improve future guarantee policies and risk monitoring.

## Approach

- **Semi-supervised learning**: Leverage both labeled and unlabeled vehicle data to identify dealership risk profiles.
- **Exploratory Data Analysis (EDA)**: Understand features like LIGHTY, odometer readings, and vehicle types.
- **Feature engineering**: Focused on vehicle behavior, seller history, and return likelihood.
- **Modeling**: Evaluated ensemble methods like Random Forest and XGBoost alongside traditional supervised models (on labeled subset).
- **Insights**: Derived dealership-level patterns and risk probabilities for unlabeled data.
