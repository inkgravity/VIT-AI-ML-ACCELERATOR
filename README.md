# Machine Learning Portfolio

## Overview
This repository contains machine learning projects focusing on classification algorithms and data preprocessing techniques. Each project demonstrates end-to-end ML workflows from data cleaning to model evaluation.

## Current Projects

### 1. Titanic Survival Prediction
**Algorithm:** Logistic Regression  
**Dataset:** Kaggle Titanic Competition  
**Goal:** Predict passenger survival based on characteristics

**Key Features:**
- Data preprocessing (handling missing values, encoding categorical variables)
- Feature engineering with one-hot encoding
- Model training and evaluation
- Confusion matrix analysis

### 2. E-Commerce Shipping Prediction
**Algorithm:** Logistic Regression  
**Dataset:** Customer Analytics (Kaggle)  
**Goal:** Predict if shipments will reach on time

**Results:**
- Model Accuracy: 65.36%
- Confusion Matrix: [[533, 362], [400, 905]]
- Better at predicting on-time deliveries vs. late shipments

**Key Insights:**
- 905 correct on-time predictions vs. 533 correct late predictions
- 362 false positives (predicted on-time but actually late) - critical for customer satisfaction

## Key Concepts Covered

### Feature Encoding Techniques
**Label Encoding** - For ordinal categorical variables:
- Product importance: low → medium → high
- Maintains natural ordering

**One-Hot Encoding** - For nominal categorical variables:
- Gender, warehouse location, shipping mode
- Avoids false ordering assumptions

### Data Preprocessing
- Missing value imputation
- Feature scaling with StandardScaler
- Handling categorical variables

### Model Evaluation
- Accuracy metrics
- Confusion matrix interpretation
- Understanding True/False Positives and Negatives
- Business impact analysis

## Technologies Used
- **Python Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn
- **Algorithms:** Logistic Regression
- **Tools:** Jupyter Notebooks, StandardScaler, LabelEncoder

## Key Learnings
- **Logistic Regression is classification, not regression** despite the name
- **Logistic Regression is a commonly used classification algorithm for binary classification** that predicts categories rather than continuous values
- **Logistic regression works by estimating probabilities** between 0 and 1, then applying a threshold (typically 0.5) to make binary predictions
- StandardScaler is crucial for distance-based algorithms
- Feature encoding choice depends on variable type (ordinal vs nominal)
- Confusion matrix provides deeper insights than accuracy alone
- Business context matters when interpreting model errors

## Future Work
This portfolio will expand to include:
- Additional classification algorithms (Random Forest, SVM)
- Regression algorithms
- Clustering techniques
- Deep learning applications
- Advanced feature engineering methods

## Files Structure
```
├── ExerciseLogisticRegression.ipynb    # Titanic survival prediction
├── E_CommerceLogisticsRegression.ipynb # Shipping time prediction  
└── README.md                          # This file
```

---
*This repository demonstrates practical machine learning applications with real-world datasets and business implications.*