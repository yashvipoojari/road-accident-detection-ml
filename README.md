# Road Accident Detection System using Machine Learning

## Overview
This project implements a Machine Learning–based Road Accident Detection System aimed at identifying accident-prone scenarios from traffic-related data. The objective is to enhance road safety by enabling timely detection and analysis of potential accidents using data-driven techniques.

## Tech Stack
- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- OpenCV (if image-based features are used)

## Dataset
- Source: Kaggle
- The dataset contains traffic and road-related attributes used to classify accident occurrences.
- Includes features such as vehicle parameters, environmental conditions, and accident indicators.

## Methodology
1. Data cleaning and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering and selection  
4. Model training and evaluation  
5. Performance comparison of multiple classifiers  

## Models Implemented
- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)  

## Results
The Random Forest model achieved the best overall performance:

- **Accuracy:** 89.2%  
- **Precision:** 88%  
- **Recall:** 87%  
- **F1-score:** 0.875  

These results demonstrate the effectiveness of machine learning techniques in identifying accident-prone scenarios from structured traffic data.

## How to Run the Project

```bash
pip install -r requirements.txt
python src/train.py
