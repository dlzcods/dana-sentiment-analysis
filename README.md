# Sentiment Analysis of Reviews on Dana Apps in Play Store
This project aims to design a deep learning model with certain schemes to analyze the sentiment of each user review which is then evaluated with predefined objectives. 

## Objective
- Training and test accuracy of at least 92%
- The model was able to classify 3 different classes: negative, neutral, and positive

## Dataset
To support the defined objectives, the dataset was obtained from independent scapping with a total of 139500 reviews in Indonesian.

## Modeling
### 1. Scheme 1
Model: Sequential
Feature Extraction: TF-IDF
Data Splitting: 80/20

### 2. Scheme 2
Model: Sequential + Convolutional
Feature Extraction: TF-IDF
Data Splitting: 70/30

### 3. Scheme 3
Model: Sequential + Convolutional
Feature Extraction: TF-IDF
Data Splitting: 80/20

## Model Evaluation
### Summary
| Scheme | Train Accuracy | Test Accuracy |
|--------|----------------|---------------|
| 1      | 97             | 92            |
| 2      | 97             | 94            |
| 3      | 97             | 91            |

