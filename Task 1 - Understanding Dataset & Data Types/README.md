# 📌 AI & ML Internship  
## 📊 Task 1 – Understanding Dataset & Data Types  

---

## 🔍✨ Objective  
The objective of this task is to **explore and understand the dataset** before applying any Machine Learning models.  
This includes identifying **data types**, analyzing **data quality**, and evaluating **ML suitability**.

> 💡 *“A strong ML model begins with a well-understood dataset.”*

---

## 🛠️ Tools & Technologies Used  
🔹 **Python**  
🔹 **Pandas**  
🔹 **NumPy**  
🔹 **Jupyter Notebook / Google Colab**

---

## 📂 Dataset Used  
### 🚢 Titanic Dataset  

The dataset contains detailed information about passengers such as:  
👤 Gender  
🎟️ Passenger Class  
🎂 Age  
💰 Fare  
❤️ Survival Status  

Each row represents **one passenger**, and each column represents **one feature**.

---

## 🧭 Task Activities Performed  

### 📥 1️⃣ Dataset Loading  
✔ Loaded the dataset using **Pandas**  
✔ Displayed the **first and last few rows** to understand the data structure  

---

### 🧩 2️⃣ Data Type Identification  
Features were manually classified as:

🔢 **Numerical Features** – Age, Fare, SibSp, Parch  
🏷️ **Categorical Features** – Sex, Embarked, Ticket, Cabin  
📊 **Ordinal Features** – Pclass  
🔘 **Binary Features** – Survived  

This classification helps in selecting appropriate preprocessing techniques.

---

### 🔍 3️⃣ Data Inspection  
✔ Used `df.info()` to analyze:
- Data types
- Missing values  

✔ Used `df.describe()` to understand:
- Statistical summaries
- Data distribution
- Potential outliers  

---

### 🧪 4️⃣ Categorical Data Analysis  
✔ Checked **unique values** in categorical columns  
✔ Identified features that require **encoding** before modeling  

---

### 🎯 5️⃣ Target Variable Identification  
🟢 **Target Variable:** `Survived`  
🔵 **Input Features:** All remaining columns  

This makes the dataset suitable for a **binary classification problem**.

---

### 📈 6️⃣ Dataset Suitability Analysis  
✔ Dataset size is sufficient for learning  
✔ Contains both numerical & categorical data  
✔ Well-suited for ML after preprocessing  

---

### ⚠️ 7️⃣ Data Quality Observations  
🔴 Missing values in **Age** and **Cabin** columns  
🟡 Categorical features need encoding  
🟠 Slight imbalance in the target variable  

These issues must be handled during data preprocessing.

---

## 📈 Final Outcome  
By completing this task, I gained a clear understanding of:

✅ Dataset structure and feature types  
✅ Importance of data exploration before modeling  
✅ Identifying data quality issues  
✅ Preparing datasets for machine learning workflows  

---

## 📁 Repository Structure  

Task-1-Data-Understanding/
│── 📄 titanic.csv
│── 📘 Task1_Titanic_Analysis.ipynb
│── 📝 README.md


---

## ✅ Conclusion  
This task helped build a **strong foundation in data understanding and exploratory data analysis**, which is a **critical first step** before applying any Machine Learning model.

🚀 *Understanding the data leads to better models and accurate predictions.*

---
