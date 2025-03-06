# ML-Classification

# Titanic Survival Prediction

## Overview
The Titanic passenger dataset provides an opportunity to build a classification model to predict whether a passenger would survive the disaster based on their data. This project involves data exploration, feature engineering, and training machine learning models to improve prediction accuracy.

---

## Objectives
- Explore the **Titanic dataset** to understand its structure and key features.
- Train a **Logistic Regression** model for classification.
- Implement **one-hot encoding** to enhance feature representation.
- Evaluate model performance using **training and validation accuracy**.
- Train a **Random Forest** classification model for improved accuracy.
- Submit predictions to **Kaggle** for evaluation.

---

## Tech Stack
- **Python** - Main programming language
- **Pandas & NumPy** - Data manipulation and analysis
- **Scikit-learn** - Machine learning model training
- **Matplotlib & Seaborn** - Data visualization
- **Kaggle** - Model evaluation and submission

---

## Dataset
The Titanic dataset includes passenger information such as:
- **Survival** (0 = No, 1 = Yes)
- **Pclass** (Passenger class: 1st, 2nd, 3rd)
- **Name, Sex, Age**
- **SibSp & Parch** (Number of siblings/spouses and parents/children aboard)
- **Ticket, Fare** (Ticket number and fare paid)
- **Cabin, Embarked** (Cabin number and embarkation port)

---

## Project Workflow
### 1. **Exploratory Data Analysis (EDA)**
- Load the dataset using Pandas.
- Handle missing values and analyze feature distributions.
- Visualize survival trends based on various features.

### 2. **Feature Engineering & Preprocessing**
- Convert categorical variables using **one-hot encoding**.
- Normalize numerical features where necessary.
- Handle missing values in columns like `Age`, `Cabin`, and `Embarked`.

### 3. **Train a Logistic Regression Model**
- Split data into **training** and **validation** sets.
- Train a Logistic Regression model and calculate accuracy.

### 4. **Train a Random Forest Model**
- Implement a **Random Forest Classifier**.
- Tune hyperparameters for better accuracy.
- Compare model performance with Logistic Regression.

### 5. **Evaluate Model Performance**
- Calculate **training and validation accuracy**.
- Use **confusion matrix and classification report** for performance analysis.

### 6. **Submit Predictions to Kaggle**
- Generate predictions on test data.
- Save results in Kaggle submission format.
- Upload and evaluate the model’s performance.


---

## Results & Learnings
- Gained insights into **feature importance** and data preprocessing.
- Compared the performance of **Logistic Regression** and **Random Forest**.
- Learned how to handle **categorical data with one-hot encoding**.

---

## License
This project is licensed under the MIT License.
