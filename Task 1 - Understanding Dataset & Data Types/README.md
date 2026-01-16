# 📌 AI & ML Internship  
## 📊 Task 1 – Understanding Dataset & Data Types  

---

## 🔍✨ Objective  
The objective of this task is to explore and understand multiple datasets before applying any Machine Learning models.  
This includes identifying data types, analyzing data quality, and evaluating ML suitability.

> 💡 “A strong Machine Learning model begins with a well-understood dataset.”

---

## 🛠️ Tools & Technologies Used  
- Python  
- Pandas  
- NumPy  
- Jupyter Notebook / Google Colab  

---

## 📂 Datasets Used  

### 🚢 Dataset 1: Titanic Dataset  

This dataset contains detailed information about Titanic passengers such as:  
- Gender  
- Passenger Class  
- Age  
- Fare  
- Survival Status  

Each row represents one passenger, and each column represents one feature.  
This dataset is mainly used for classification problems.

---

### 🎓 Dataset 2: Students Performance Dataset  

This dataset contains academic performance data of students, including:  
- Gender  
- Lunch type  
- Parental education  
- Test preparation status  
- Math, Reading, and Writing scores  

Each row represents one student, and each column represents one feature.  
This dataset is mainly used for regression and performance prediction problems.

---

## 🧭 Task Activities Performed  

### 📥 1️⃣ Dataset Loading  
- Loaded both datasets using Pandas  
- Displayed the first and last few rows to understand structure and columns  

---

### 🧩 2️⃣ Data Type Identification  

**Titanic Dataset**  
- Numerical Features: Age, Fare, SibSp, Parch  
- Categorical Features: Sex, Embarked, Ticket, Cabin  
- Ordinal Features: Pclass  
- Binary Features: Survived  

**Students Performance Dataset**  
- Numerical Features: Math score, Reading score, Writing score  
- Categorical Features: Gender, Lunch, Parental Education, Test Preparation  

This classification helps in choosing suitable preprocessing and modeling techniques.

---

### 🔍 3️⃣ Data Inspection  
- Used df.info() to analyze data types, dataset size, and missing values  
- Used df.describe() to understand statistical summaries and data distribution  

---

### 🧪 4️⃣ Categorical Data Analysis  
- Checked unique values in categorical columns  
- Identified features requiring encoding before modeling  

---

### 🎯 5️⃣ Target Variable Identification  

**Titanic Dataset**  
- Target Variable: Survived  
- Input Features: All remaining columns  
- Problem Type: Binary Classification  

**Students Performance Dataset**  
- Target Variables:  
  - Math score  
  - Reading score  
  - Writing score  
- Problem Type: Regression  

---

### 📈 6️⃣ Dataset Suitability Analysis  
- Both datasets contain numerical and categorical features  
- Dataset sizes are sufficient for learning basic ML models  
- Suitable for ML after preprocessing  

---

### ⚠️ 7️⃣ Data Quality Observations  

**Titanic Dataset**  
- Missing values in Age and Cabin columns  
- Categorical features require encoding  
- Slight imbalance in the target variable  

**Students Performance Dataset**  
- No missing values  
- Categorical features require encoding  

---

## 📈 Final Outcome  
By completing this task, I gained a clear understanding of:
- Dataset structure and feature types  
- Differences between classification and regression datasets  
- Importance of data exploration before modeling  
- Identifying data quality issues  
- Preparing datasets for machine learning workflows  

---

## 📁 Repository Structure  

