# AI-ML-Internship-Task-10
## Task 10: KNN – Handwritten Digit Classification

## 📌 Objective
To classify handwritten digits using the K-Nearest Neighbors (KNN) algorithm and evaluate model performance for different values of K.

---

## 🛠 Tools & Libraries
- Python  
- Scikit-learn  
- Matplotlib  
- Google Colab  

---

## 📊 Dataset
- **Digit Recognizer (MNIST)** – Kaggle  
- Contains 28×28 pixel grayscale images of handwritten digits (0–9).

---

## 🧪 Steps Performed
1. Loaded the MNIST digit dataset from Kaggle.
2. Visualized sample digit images with their labels.
3. Split the dataset into training and testing sets.
4. Applied feature scaling using StandardScaler since KNN is distance-based.
5. Trained KNN model with K = 3 and calculated accuracy.
6. Tested multiple K values (3, 5, 7, 9) and recorded accuracy.
7. Plotted Accuracy vs K graph to select the best K.
8. Generated confusion matrix to analyze misclassified digits.
9. Displayed sample test images with predicted labels.

---

## 📈 Results
- Accuracy varies with different K values.
- Best K is chosen based on the highest accuracy from the Accuracy vs K plot.
- Confusion matrix visualizes correct and incorrect predictions for each digit class.

---


## ✅ Conclusion
This project demonstrates handwritten digit classification using the KNN algorithm. It highlights the importance of feature scaling, choosing the correct K value, and evaluating model performance using accuracy and confusion matrix.
