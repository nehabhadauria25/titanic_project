# 🚢 Titanic Survival Prediction using Machine Learning

A machine learning project that predicts whether a passenger survived the Titanic disaster using multiple classification algorithms. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of six machine learning models.

---

## 📌 Project Overview

The sinking of the RMS Titanic is one of the most well-known maritime disasters in history. This project aims to predict passenger survival based on various features such as age, gender, passenger class, fare, and family information.

The primary objective was not only to build a predictive model but also to compare the performance of different machine learning algorithms on the same dataset.

---

## 📂 Dataset

**Source:** Kaggle - Titanic: Machine Learning from Disaster

The dataset contains passenger information including:

- Passenger Class (Pclass)
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked
- Survival Status (Target)

---

## 🛠️ Project Workflow

1. Data Loading
2. Data Cleaning
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Encoding Categorical Variables
7. Feature Scaling
8. Model Training
9. Model Evaluation
10. Model Comparison

---

## 📊 Exploratory Data Analysis

Performed analysis to understand:

- Survival distribution
- Gender-wise survival
- Passenger class distribution
- Age distribution
- Fare distribution
- Correlation between features

---

## ⚙️ Data Preprocessing

- Removed unnecessary columns
- Handled missing values
- Encoded categorical variables
- Applied feature scaling where required
- Split dataset into training and testing sets

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

---

## 📈 Model Performance

| Model | Test Accuracy |
|--------|--------------:|
| Support Vector Machine | **82.12%** |
| K-Nearest Neighbors | 81.60% |
| Random Forest | 81.56% |
| Logistic Regression | ~81% |
| Decision Tree | ~81% |
| Gaussian Naive Bayes | 77.09% |

---

## 🏆 Best Performing Model

**Support Vector Machine (SVM)**

- Test Accuracy: **82.12%**
- Excellent generalization
- Minimal overfitting
- Required feature scaling

---

## 📌 Key Observations

- Logistic Regression provided a strong baseline.
- Decision Tree was easy to interpret but prone to overfitting.
- Random Forest improved stability using ensemble learning.
- SVM achieved the highest accuracy.
- KNN performed well after selecting the optimal value of K.
- Gaussian Naive Bayes was computationally efficient but less accurate due to its feature independence assumption.

---

## 🧰 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
Titanic-ML-Project/
│
├── data/
│   ├── train.csv
│   ├── test.csv
│
├── notebooks/
│   └── titanic_analysis.ipynb
│
├── images/
│   ├── accuracy_comparison.png
│   ├── feature_importance.png
│   ├── confusion_matrix_svm.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/nehabhadauria25/titanic_project.git
```

Move into the project directory

```bash
cd titanic_project
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
notebooks/titanic_analysis.ipynb
```

Run all cells.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Visualization
- Feature Engineering
- Feature Scaling
- Model Selection
- Model Evaluation
- Classification Algorithms
- Machine Learning Workflow

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- ROC-AUC comparison
- Model deployment using Streamlit
- Feature selection techniques
- Ensemble boosting algorithms (XGBoost, LightGBM)

---

## 👩‍💻 Author

**Neha**

B.Tech CSE-AI

This project was developed as part of my machine learning learning journey to strengthen my understanding of supervised learning algorithms and model evaluation.
