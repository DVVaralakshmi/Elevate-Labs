AI & ML INTERNSHIP  

**✅ Task 16: Hyperparameter Tuning using GridSearchCV**

---

**📌 Objective**

The objective of this task is to optimize machine learning model performance using GridSearchCV by tuning hyperparameters and comparing the tuned model with the default model.

---

**📂 Dataset**

Primary: Breast Cancer Wisconsin Dataset (sklearn)  
Alternative: Titanic Dataset  

---

**🛠 Tools**

Python  
Scikit-learn (GridSearchCV)  
Pandas  
Jupyter Notebook / Google Colab  

---

**⚙ Task Implementation**

**1️⃣ Data Loading & Preprocessing**  
- Loaded dataset using sklearn / pandas  
- Handled missing values (if any)  
- Applied feature scaling (for SVM model)  

**2️⃣ Train-Test Split**  
- Split dataset into training and testing sets  
- Used random_state for reproducibility  

**3️⃣ Model Selection**  
- Selected classification model (SVM / Random Forest)  

**4️⃣ Hyperparameter Grid Definition**  

For SVM:  
- C  
- kernel  
- gamma  

For Random Forest:  
- n_estimators  
- max_depth  
- min_samples_split  

**5️⃣ Applying GridSearchCV**  
- Used cross-validation  
- Selected accuracy as scoring metric  
- Trained model on training data  

**6️⃣ Extracting Best Parameters**  
- Retrieved best parameters  
- Retrieved best estimator  

**7️⃣ Performance Comparison**  
- Evaluated default model accuracy  
- Evaluated tuned model accuracy  
- Compared results using a performance table  

---

**📊 Deliverables**

- Notebook with GridSearchCV implementation  
- Best parameters output  
- Performance comparison table  

---
**🚀 Final Outcome**

By completing this task, I learned model optimization techniques, the importance of cross-validation, and how hyperparameter tuning improves machine learning performance.
