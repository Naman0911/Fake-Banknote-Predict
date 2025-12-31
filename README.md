# Fake Banknote Detection

This repository contains a **Machine Learning project** to detect **genuine vs. forged banknotes** using statistical features extracted from banknote images. The model achieves an accuracy of **99.8%**, demonstrating strong performance on this binary classification task.

---

## 🔍 Project Overview

Detecting counterfeit banknotes is crucial in financial systems. This project uses the **Banknote Authentication Dataset** and applies a **K-Nearest Neighbors (KNN)** classifier to classify banknotes as real or fake based on numerical image features.

---

## 📦 Dataset

**Banknote Authentication Dataset (UCI)**

### Features

| Feature   | Description |
|----------|-------------|
| Variance | Variance of the wavelet transformed image |
| Skewness | Asymmetry of the image distribution |
| Kurtosis | Peakedness of the image distribution |
| Entropy  | Randomness in the image texture |
| Class    | 0 → Forged, 1 → Genuine |

---

## 🧠 Model Used

- Algorithm: **K-Nearest Neighbors (KNN)**
- Distance Metric: Euclidean
- Feature Scaling: StandardScaler

---

## 📊 Results

- **Accuracy:** **99.8%**
- Very low misclassification
- High precision and recall

---

## 🚀 How to Run

```bash
git clone https://github.com/Naman0911/Fake-Banknote-Predict.git
cd Fake-Banknote-Predict
pip install -r requirements.txt
python fake_banknote_knn.py
```

---

## 📈 Evaluation

- Confusion Matrix
- Accuracy Score
- Precision, Recall, F1-Score

---

## 📚 References

- UCI Machine Learning Repository – Banknote Authentication Dataset  
- scikit-learn documentation

---

## 📝 Conclusion

The KNN model performs exceptionally well on this low-dimensional and well-structured dataset, achieving near-perfect accuracy in detecting fake banknotes.
