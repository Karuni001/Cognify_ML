# Cognify_ML
# 🍽️ Restaurant Data Analysis and Prediction

A comprehensive machine learning project using real-world restaurant data to perform prediction, recommendation, classification, and location-based analysis.

---

## 📁 Dataset

Used a restaurant dataset containing information like:
- Restaurant name, location, cuisines, pricing
- Online delivery, table booking options
- Aggregate ratings and votes

---

## ✅ Tasks Overview

### 🔹 **Task 1: Rating Prediction**
- **Goal**: Predict a restaurant's rating based on cost, location, services, etc.
- **Model**: Random Forest Regressor
- **Metrics**: RMSE, R² Score
- **Output**: Feature importance graph and evaluation scores

### 🔹 **Task 2: Recommendation System**
- **Goal**: Recommend similar restaurants based on user’s cuisine, city, and price range
- **Method**: Content-based filtering using TF-IDF and Cosine Similarity
- **Output**: Top 5 personalized restaurant recommendations

### 🔹 **Task 3: Cuisine Classification**
- **Goal**: Predict the primary cuisine of a restaurant using other metadata
- **Model**: Random Forest Classifier
- **Metrics**: Accuracy, Precision, Recall, Confusion Matrix
- **Output**: Classification report and heatmap

### 🔹 **Task 4: Location-Based Analysis**
- **Goal**: Explore restaurants across different cities using map and statistical plots
- **Tools**: Plotly, Seaborn
- **Visuals**: 
  - Interactive location map
  - Top 10 cities by restaurant count, average rating, and pricing

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, NumPy**
- **scikit-learn**
- **Matplotlib, Seaborn**
- **Plotly**
- **TF-IDF / Cosine Similarity**
- **PyCharm IDE**

---
