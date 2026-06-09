# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview
This project applies Machine Learning techniques to predict whether a passenger survived the Titanic disaster. The model is trained using passenger information such as age, gender, passenger class, fare, and family details.

The project demonstrates a complete end-to-end Machine Learning workflow including data preprocessing, exploratory data analysis, feature engineering, model training, and performance evaluation.

---

## 🎯 Objective
The main objective of this project is to build a classification model that predicts passenger survival based on historical Titanic dataset records.

---

## 📂 Dataset
- **Dataset Source:** Kaggle Titanic Dataset
- **Dataset Size:** 891 rows × 12 columns

### Features Used
- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

### Target Variable
- Survived

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 🔄 Project Workflow
1. Data Loading  
2. Data Cleaning and Missing Value Handling  
3. Exploratory Data Analysis (EDA)  
4. Feature Encoding  
5. Feature Selection  
6. Train-Test Split  
7. Machine Learning Model Training  
8. Model Evaluation and Comparison  

---

## 📊 Exploratory Data Analysis
Several visualizations were created to understand passenger survival patterns:

- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Fare Distribution
- Correlation Heatmap

---

## 🤖 Machine Learning Models Used

### 1. Logistic Regression
Used as a baseline classification model for survival prediction.

### 2. Random Forest Classifier
Used to improve prediction performance using ensemble learning techniques.

---

## 📈 Results

| Model | Accuracy |
|------|----------|
| Logistic Regression | 79.89% |
| Random Forest Classifier | 82.68% |

✅ **Best Performing Model:** Random Forest Classifier

---

## 📌 Key Insights
- Female passengers had higher survival rates compared to male passengers
- First-class passengers were more likely to survive
- Fare and age influenced survival probability
- Random Forest performed better than Logistic Regression

---

## 📊 Model Evaluation
The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

---

## 🚀 Future Improvements
Possible future improvements include:

- Hyperparameter tuning
- Advanced feature engineering
- Cross-validation techniques
- Using advanced algorithms such as XGBoost
- Deployment using Flask or Streamlit

---

## 🧠 Key Learnings
This project improved understanding of:

- Data preprocessing techniques
- Handling missing values
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine Learning model building
- Model evaluation techniques

---

## 👨‍💻 Author
**Siva Durga Vinay Chowdary**  
Aspiring Data Analyst | Machine Learning Enthusiast

---

## ⭐ Conclusion
This project successfully demonstrated the complete Machine Learning workflow using the Titanic dataset. It provided valuable hands-on experience in predictive analytics, data visualization, and classification model development.

---

## 📎 Project Files
- `Titanic_Survival_Prediction.ipynb`
- `README.md`
- `train.csv`
- `Project_Report.pdf`

---
