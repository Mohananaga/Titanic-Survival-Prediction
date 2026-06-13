# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning techniques. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation using the **Random Forest Classifier**.

The goal is to demonstrate an end-to-end Machine Learning workflow that can be used as a beginner portfolio project for Data Science and AI roles.

---

# 📊 Dataset

The dataset is taken from the **Kaggle Titanic: Machine Learning from Disaster** competition.

It contains information about passengers such as:

* Passenger Class (Pclass)
* Name
* Sex
* Age
* Number of Siblings/Spouses (SibSp)
* Number of Parents/Children (Parch)
* Ticket Number
* Fare
* Cabin
* Embarked Port
* Survival Status (Target Variable)

Target Variable:

* **Survived = 1**
* **Not Survived = 0**

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

* Loaded dataset using Pandas
* Checked missing values
* Filled missing values in **Age** using Median
* Filled missing values in **Embarked** using Mode
* Replaced missing Cabin values with **Unknown**
* Converted categorical variables into numerical values using Label Encoding
* Removed unnecessary columns:

  * PassengerId
  * Name
  * Ticket

---

# 📈 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the dataset.

Visualizations include:

* Missing Value Heatmap
* Survival Count
* Survival by Gender
* Age Distribution
* Correlation Heatmap
* Feature Importance Plot

EDA helped identify important relationships between passenger attributes and survival.

---

# 🤖 Machine Learning Model

The following Machine Learning algorithm was used:

* Random Forest Classifier

Steps:

1. Data Preprocessing
2. Train-Test Split
3. Model Training
4. Prediction
5. Model Evaluation

The trained model was also saved using **Joblib**.

---

# 📉 Accuracy

The model achieved an accuracy of approximately **80–85%** depending on preprocessing and random state.

Evaluation metrics include:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score
* Classification Report

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

---

# 📂 Project Structure

```
Titanic-Survival-Prediction/
│
├──data/
       train.csv
       test.csv
├── titanic.ipynb
├── requirements.txt
├── README.md
├── random_forest_model.pkl

```

---

# 🚀 Future Improvements

* Perform Hyperparameter Tuning
* Compare multiple Machine Learning models
* Add Feature Engineering using passenger titles
* Build a Streamlit Web Application
* Deploy the project online
* Improve Kaggle competition score using advanced techniques

---

# 📚 Learning Outcomes

This project demonstrates:

* Data Cleaning
* Data Visualization
* Feature Engineering
* Machine Learning
* Model Evaluation
* Python Programming
* GitHub Project Management

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
