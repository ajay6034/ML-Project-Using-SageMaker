

# 📱 Mobile Price Classification using AWS SageMaker (Scikit-Learn)

## 📌 Project Overview

This project builds and deploys a **Mobile Price Classification Model** using:

* **Python**
* **Scikit-Learn (Random Forest)**
* **AWS SageMaker**
* **Boto3**
* **Pandas**

The model classifies mobile phones into price categories based on their specifications.

---

## 🏗️ Architecture Flow

1. Load dataset using Pandas
2. Perform data exploration & preprocessing
3. Split data into train and test sets
4. Upload processed data to Amazon S3
5. Create custom Scikit-Learn training script
6. Train model using SageMaker SKLearn Estimator
7. Evaluate performance


# 🤖 Model Training (Custom Script)

A custom `script.py` is created with:

* `RandomForestClassifier`
* Model training logic
* Evaluation metrics:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
  * Confusion Matrix
  * ROC Curve
* Model saving using `joblib`

---




## 📈 Model Used

**Algorithm:** Random Forest Classifier
**Framework:** Scikit-Learn 1.2-1
**Instance Type:** ml.m5.large



## 🎯 Key Learnings

* End-to-end ML pipeline using SageMaker
* Custom training script integration
* S3 data pipeline
* Cloud-based scalable model training
* Hyperparameter configuration in SageMaker
---

## 📌 Future Improvements

* Hyperparameter tuning
* Model deployment endpoint
* CI/CD integration
* MLOps pipeline automation
* Feature importance visualization

