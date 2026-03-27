# AI_ML_Internship_Tasks

## Task 1: Iris Dataset Exploration
- **Objective:** Explore and visualize the Iris dataset to understand feature distributions and relationships.
- **Dataset Used:** Iris dataset (seaborn)
- **Models Applied:** None
- **Key Results:** Scatter plots show clear separation of species.

## Task 2: Heart Disease Prediction
- **Objective:** Predict risk of heart disease using health data.
- **Dataset Used:** Heart Disease UCI dataset
- **Models Applied:** Logistic Regression, Decision Tree
- **Key Results:** Accuracy = 0.85; Chest pain, cholesterol, and age are key predictors.

## Task 3: House Prices Prediction
- **Objective:** Predict house prices based on property features.
- **Dataset Used:** House Price Prediction dataset
- **Models Applied:** Linear Regression
- **Key Results:** MAE = 15000, RMSE = 20000; Predicted prices closely match actual.

- # AI/ML Advanced Internship Tasks

This repository contains solutions to 3 advanced AI/ML tasks completed as part of an AI/ML Engineering Internship. 


# Task 1: News Topic Classifier Using BERT

## Objective
To fine-tune a transformer-based model (BERT) to classify news headlines into different topic categories.

## Dataset
AG News Dataset (via Hugging Face Datasets)

## Methodology
- Loaded dataset using Hugging Face `datasets`
- Tokenized text using BERT tokenizer
- Fine-tuned `bert-base-uncased` model
- Used Trainer API for training
- Evaluated model using:
  - Accuracy
  - F1-score

## Results
- Successfully classified news into categories
- Achieved good accuracy on validation set
- Demonstrated transfer learning using pretrained transformers

## Skills Gained
- NLP using Transformers
- Transfer learning & fine-tuning
- Text classification
- Model evaluation metrics

---

#  Task 2: End-to-End ML Pipeline (Customer Churn)

## Objective
To build a reusable and production-ready machine learning pipeline for predicting customer churn.

## Dataset
Telco Customer Churn Dataset (Kaggle)

## Methodology
- Data preprocessing using:
  - StandardScaler (numerical data)
  - OneHotEncoder (categorical data)
- Combined preprocessing using `ColumnTransformer`
- Built pipeline using `Pipeline`
- Trained models:
  - Logistic Regression
  - Random Forest
- Used `GridSearchCV` for hyperparameter tuning
- Exported model using `joblib`

## Results
- Built a complete ML pipeline
- Achieved reliable prediction accuracy
- Created reusable and deployable model

## Skills Gained
- ML pipeline construction
- Hyperparameter tuning
- Model deployment readiness
- Feature preprocessing


# Task 3: Multimodal Housing Price Prediction

## Objective
To predict housing prices using both tabular data and image data.

## Dataset
- Housing tabular dataset
- House images dataset

## Methodology
- Used MobileNetV2 (CNN) for image feature extraction
- Processed tabular features (area, bedrooms, etc.)
- Combined image + tabular features (feature fusion)
- Trained Linear Regression model
- Evaluated using:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

## Results
- Successfully implemented multimodal learning pipeline
- Demonstrated feature fusion from different data types
- Generated predictions with acceptable error rates

## Skills Gained
- Multimodal machine learning
- CNN feature extraction
- Feature fusion
- Regression modeling

---

# Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Hugging Face Transformers
- Matplotlib / Seaborn
- Joblib

---

# Conclusion

These tasks demonstrate strong practical understanding of:
- Deep Learning (BERT, CNNs)
- Machine Learning pipelines
- Data preprocessing and feature engineering
- Model evaluation and deployment concepts


