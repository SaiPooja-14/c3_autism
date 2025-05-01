
# Autism Prediction using Machine Learning

## Project Overview

This project aims to predict Autism Spectrum Disorder (ASD) using machine learning techniques. By analyzing screening data, the system helps identify individuals at risk of autism, aiding early diagnosis and intervention.

## Problem Statement

Autism is a neurodevelopmental disorder that affects communication and behavior. Early diagnosis is critical but often delayed. This project proposes a machine learning-based approach to predict ASD from screening data, improving the chances of early detection.

## Existing System

Traditional ASD screening relies on manual questionnaires and medical evaluations, which can be time-consuming and require expert interpretation.

##  Proposed System

Our system leverages machine learning algorithms to automate and enhance ASD prediction:
- Preprocessing of questionnaire data
- Feature selection for improved accuracy
- Model training and evaluation using various classifiers
- Deployment-ready framework for future integration

##  Technologies Used

- Python  
- Pandas, NumPy – Data processing  
- Scikit-learn – Machine learning models  
- Matplotlib, Seaborn – Data visualization

## Dataset

- Source: Autism Screening Adult Data Set (from UCI or similar)
- Features: Age, gender, screening questions (A1–A10), family history, etc.
- Target: Class label indicating ASD risk

## ML Algorithms Used

- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)

## Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix

## Results

Among all models, the Random Forest classifier showed the highest accuracy, offering a balance between performance and interpretability.

## Conclusion

The machine learning-based approach shows promising results in predicting autism, potentially assisting medical professionals in early screening and intervention.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/SaiPooja-14/c3_autism
   cd autism-prediction-ml
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script:
   ```bash
   python autism_prediction.py
   ```

