# Drug Classification using Machine Learning

## Overview
#### This project predicts the type of drug a patient should take based on their medical attributes using machine learning models. Multiple classification models are trained and evaluated to determine the most accurate method.

## Dataset

#### The dataset used is drug200.csv, which contains the following features:

* Age: Patient's age

* Sex: Male (M) or Female (F)

* BP: Blood pressure levels (LOW, NORMAL, HIGH)

* Cholesterol: Cholesterol levels (NORMAL, HIGH)

* Na_to_K: Sodium-to-Potassium ratio in blood

* Drug: Target variable (Type of drug prescribed)

## Steps Involved

### 1. Load Dataset

#### Read the drug200.csv file using pandas.

### 2. Data Preprocessing

#### Encode categorical variables (Sex, BP, Cholesterol) using LabelEncoder.

#### Split the dataset into features (X) and target (y).

#### Perform a train-test split (70% training, 30% testing).

### 3. Model Selection & Training

#### The following machine learning models were used:

* Logistic Regression

* Decision Tree Classifier

* Random Forest Classifier

* K-Nearest Neighbors (KNN)

* Support Vector Machine (SVM)

* Naive Bayes

#### Each model is trained on the training data and tested on unseen test data.

### 4. Model Evaluation

#### Models are evaluated using:

* Accuracy

* Precision, Recall, and F1-Score

### 5. Predictions for New Patients

#### A sample patient’s data is provided, and the trained models predict the recommended drug.

### Results

* Decision Tree and Random Forest performed the best, as they can effectively handle categorical and numerical data.

* Precision, Recall, and F1-Score were used to evaluate model efficiency beyond accuracy.

### How to Run the Project

#### 1. Install the necessary libraries:

* pip install numpy pandas scikit-learn matplotlib seaborn

#### 2. Run the Python script:

* python main.py

### Future Improvements

* Apply feature scaling for models like KNN and SVM.

* Use GridSearchCV for hyperparameter tuning.

* Implement more advanced models like XGBoost or Neural Networks.

### Conclusion

This project successfully classifies drugs based on patient attributes. The Decision Tree and Random Forest classifiers were the most accurate models for this task.


