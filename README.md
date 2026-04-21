# 🚢 Titanic Survival Prediction (Machine Learning Project)

## 👨‍💻 Author

**Aman Khanal**
GitHub: [amanml2026](https://github.com/amanml2026)

---

## 📌 Project Overview

This project predicts passenger survival in the Titanic disaster using Machine Learning techniques.
It includes **data preprocessing, feature engineering, exploratory data analysis (EDA), model training, evaluation, and pipeline creation**.

---

## 🎯 Problem Statement

Predict whether a passenger survived or not based on features such as:

* Age
* Sex
* Passenger Class (Pclass)
* Fare
* Family Size
* Embarked Location
* Title (Mr, Mrs, Miss, etc.)

---

## 📊 Dataset

* Source: Kaggle Titanic Dataset
* File used: `Titanic-Dataset.csv`

---

## ⚙️ Workflow

### 1. Data Cleaning

* Handled missing values (Age, Embarked)
* Removed noise and unnecessary preprocessing issues

---

### 2. Feature Engineering

Created new meaningful features:

* **Family Size** = SibSp + Parch + 1
* **Family Type** = Alone / Small / Large
* **Title Extraction** from Name (Mr, Mrs, Miss, Rare)

---

### 3. Exploratory Data Analysis (EDA)

Key insights:

* Females had higher survival rate than males
* First-class passengers survived more
* Small families had better survival chances
* Higher fare correlated with survival

---

### 4. Model Building

Models used:

* Logistic Regression
* Decision Tree
* Random Forest

---

### 5. Model Evaluation

* Accuracy Score
* Classification Report
* Confusion Matrix
* Cross Validation

---

## 🧠 Final Model Selection

* Random Forest selected as final model due to better generalization
* Logistic Regression used for interpretability

---

## 📦 Model Export

Final trained model saved as:

```
pipe.pkl
```

---

## 🚀 How to Run This Project

1. Clone or download the repository
2. Open `main.ipynb` in Jupyter Notebook
3. Run all cells sequentially
4. Ensure `Titanic-Dataset.csv` is in the same folder

---

## 📌 Folder Structure

```
TitanicSurvive/
│
├── main.ipynb
├── Titanic-Dataset.csv
├── pipe.pkl
├── README.md
```

---

## 🔥 Key Learnings

* End-to-end ML pipeline creation
* Feature engineering improves model performance significantly
* Importance of model comparison
* How to structure real-world ML projects

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!
