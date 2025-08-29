# Jellyfish Species Classification  

## 📌 Overview  
This project develops a **machine learning and deep learning system** to identify jellyfish species from images, distinguishing between **safe** and **dangerous** types.  
The ultimate goal is to build a **mobile app** that enhances **diver safety in the Red Sea** through accurate and reliable jellyfish classification.  

---

## 🧪 Models Compared  
We implemented and evaluated several classification models:  
- **SVM (Support Vector Machine)** with HOG features  
- **KNN (K-Nearest Neighbors)**  
- **ANN (Artificial Neural Network)** with HOG features  
- **CNN (Convolutional Neural Network)** (end-to-end deep learning)  

---

## 📊 Results  

### 🔹 SVM (Best Traditional Model)  
- Accuracy: **86%**  
- Precision: 0.90 / 0.83  
- Recall: 0.83 / 0.90  
- F1-score: 0.86  

### 🔹 KNN  
- Accuracy: **73%**  
- Precision: 0.87 / 0.69  
- Recall: 0.54 / 0.92  
- F1-score: 0.67 / 0.79  

### 🔹 ANN  
- Accuracy: **83.5%**  
- Precision: 0.86 / 0.81  
- Recall: 0.78 / 0.88  
- F1-score: 0.82 / 0.85  

### 🔹 CNN (Best Deep Learning Model)  
- Accuracy: **91%**  
- Precision: 0.90 / 0.92  
- Recall: 0.92 / 0.90  
- F1-score: 0.91  

---

## 🏆 Conclusion  
- **CNN achieved the highest performance (91% accuracy)**, making it the most suitable model for deployment in the mobile app.  
- Traditional ML models (SVM, KNN, ANN) performed reasonably well but were outperformed by CNN.  
- The system demonstrates that **deep learning can provide robust, real-time classification** for diver safety applications.  

---

## 🚀 Future Work  
- Expand dataset with more jellyfish species.  
- Optimize CNN for **Edge AI deployment** on mobile devices.  
- Integrate the model into a **diver safety mobile app** with live camera detection.  

---
