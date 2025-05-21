# Optimized-Breast-Cancer-Detection-Using-SVC-with-GridSearchCV
This project implements a machine learning model using Support Vector Classifier (SVC) with GridSearchCV for hyperparameter tuning to enhance breast cancer classification. The approach aims to improve early detection accuracy and aid in precise diagnosis of malignant and benign tumors using the Wisconsin Breast Cancer Diagnostic (WBCD) dataset.
# Optimized Breast Cancer Detection Using SVC with GridSearchCV

## Description
This project implements a machine learning model using Support Vector Classifier (SVC) with GridSearchCV for hyperparameter tuning to enhance breast cancer classification. The approach aims to improve early detection accuracy and aid in precise diagnosis of malignant and benign tumors using the Wisconsin Breast Cancer Diagnostic (WBCD) dataset.

## Abstract
Breast cancer is a leading cause of cancer-related mortality among women, highlighting the need for accurate early diagnosis. This project presents an enhanced classification method using a Support Vector Classifier (SVC), combined with GridSearchCV for optimal hyperparameter tuning. Parameters such as regularization (C), kernel type, and gamma were optimized through 5-fold cross-validation. The optimized model significantly outperformed standard models across metrics like accuracy, precision, recall, F1 score, and AUC. This robust approach offers improved diagnostic capabilities, contributing to more reliable and timely breast cancer detection.

## Proposed Algorithm
- **Support Vector Classifier (SVC)**
- **GridSearchCV** for hyperparameter tuning

## Requirements
- Python (>=3.8 recommended)
- Flask
- scikit-learn==0.24.2
- numpy==1.24.0
- pandas

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/breast-cancer-svc-gridsearch.git


## 2. Navigate into the project directory:

cd breast-cancer-svc-gridsearch

## 3.Create and activate a virtual environment:


python -m venv venv
source venv/bin/activate        # On Windows use: venv\Scripts\activate
\
## 4.Install dependencies:

pip install -r requirements.txt
Run the Flask app:
python app.py

## 6. Open your browser and go to http://127.0.0.1:5000 to access the application.

## Dataset
Wisconsin Breast Cancer Diagnostic (WBCD) dataset from UCI Machine Learning Repository.

## Features
Upload and classify data using the trained SVC model.

Visualize predictions: malignant vs. benign tumors.

Hyperparameter tuning using GridSearchCV.

Accurate evaluation metrics (Accuracy, Precision, Recall, F1 Score, AUC).

## License
This project is licensed under the MIT License.
