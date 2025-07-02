# elevate_labs-task-6
# 🌸 Iris Dataset Classification using K-Nearest Neighbors (KNN)

This project demonstrates how to classify the Iris flower dataset using the K-Nearest Neighbors (KNN) algorithm. It includes preprocessing, model training, evaluation, and visualization of decision boundaries.

---

## 📚 Dataset

- Source: UCI Machine Learning Repository
- Features: SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm
- Target: Species (Iris-setosa, Iris-versicolor, Iris-virginica)

---

## 🧠 Algorithms & Techniques

- K-Nearest Neighbors (KNN) Classifier
- Feature Normalization using StandardScaler
- Dimensionality Reduction using PCA (for visualization)
- Model evaluation with Accuracy and Confusion Matrix

---

## 🔍 What’s Implemented

- Loading and preprocessing the Iris dataset
- Splitting data into training and testing sets
- Training KNN models with multiple K values (1, 3, 5, 7)
- Evaluating each model’s performance
- Reducing dimensions to 2D using PCA
- Visualizing decision boundaries for the best K

---

## 📊 Results

- Accuracy evaluated for each value of K
- Confusion matrices printed for detailed performance
- Clear visualization of decision boundaries in 2D space

---

## 🛠 Tools & Libraries

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

---

## 📁 Files

- `Iris.csv` — Dataset file
- `iris_knn.ipynb` — Jupyter Notebook with all steps
- `README.md` — Project overview and documentation

---

## ✨ Future Improvements

- Use GridSearchCV for optimal K selection
- Try other classifiers like SVM, Decision Trees
- Build a simple Streamlit UI for interaction

---

## 🔗 References

- UCI Iris Dataset: https://archive.ics.uci.edu/ml/datasets/iris
- scikit-learn KNN: https://scikit-learn.org/stable/modules/neighbors.html
