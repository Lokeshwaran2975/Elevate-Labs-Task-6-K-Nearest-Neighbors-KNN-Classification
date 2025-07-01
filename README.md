# Elevate-Labs-Task-6
## K-Nearest-Neighbors-KNN-Classification

This project demonstrates a practical implementation of the **K-Nearest Neighbors (KNN)** algorithm using Python and Scikit-learn. The objective is to classify data points based on similarity, evaluate the model, and visualize decision boundaries using PCA.

---

## 📌 Objective

To understand and apply the KNN classification algorithm on a real-world dataset, optimize the value of `K`, and evaluate performance using metrics and visualization techniques.

---

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** – Data loading and manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning and preprocessing  

---

## 📁 Dataset

A CSV file containing a classification dataset is used. The dataset includes multiple features and a target column (label). Features are normalized using `StandardScaler` to ensure fair distance measurement in KNN.

---

## 🔄 Project Workflow

### 1. Data Preprocessing
- Load CSV dataset using Pandas
- Handle missing/null values
- Normalize features using `StandardScaler`
- Encode class labels (if categorical)

### 2. Model Development
- Split data into training and testing sets (80/20)
- Train KNN classifier using `KNeighborsClassifier` (initially with K=5)
- Predict on the test set

### 3. Evaluation Metrics
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-score)**

### 4. K Optimization
- Loop over multiple `K` values (1 to 20)
- Plot Accuracy vs. K graph to identify optimal K

### 5. Visualization
- Dimensionality reduction using PCA (2D projection)
- Plot KNN decision boundaries
- Scatter plot showing classification regions

---

## 📊 Results

- Best K is selected based on maximum accuracy on validation set.
- Confusion matrix and report highlight model performance.
- Decision boundary helps visualize class separation.

---

## 📷 Visual Outputs

- Accuracy vs. K-value line plot

  ![Accuracy vs Value](https://github.com/user-attachments/assets/7c1e81b8-92a3-448e-88c5-945e1acf493c)

  
- Decision boundary using 2D PCA projection

  ![KNN Decision Boundary (2D PCA Projection)](https://github.com/user-attachments/assets/4cb18cb1-0f35-433f-9391-81534e1012f7)


---
