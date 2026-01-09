# 🌸 Iris Flower Classification | CodSoft Task 3

### 📄 Project Overview
* **Objective:** Develop a machine learning model to classify Iris flowers into their respective species based on sepal and petal measurements.
* **Domain:** Data Science / Supervised Machine Learning (Classification).
* **Problem Statement:** The Iris dataset contains measurements of 150 iris flowers from three different species: *Setosa*, *Versicolor*, and *Virginica*. The goal is to train a model that can accurately label a new flower based on its physical dimensions.
* **Context:** Completed as **Task 3** for the **CodSoft Data Science Internship** (Batch Jan 2026).

### 📊 Dataset Details
* **Source:** The standard Iris dataset (available in Scikit-Learn/Seaborn).
* **Total Samples:** 150 (50 per species).
* **Features (Inputs):**
    1.  `SepalLengthCm`: Length of the sepal (in cm).
    2.  `SepalWidthCm`: Width of the sepal (in cm).
    3.  `PetalLengthCm`: Length of the petal (in cm).
    4.  `PetalWidthCm`: Width of the petal (in cm).
* **Target (Output):** `Species` (Iris-setosa, Iris-versicolor, Iris-virginica).

### 🛠️ Tech Stack
* **Language:** Python
* **Libraries:**
    * **Pandas:** For data loading and manipulation.
    * **NumPy:** For numerical operations.
    * **Matplotlib & Seaborn:** For data visualization (pairplots, heatmaps).
    * **Scikit-Learn:** For model training, splitting data, and evaluation.
* **Environment:** Jupyter Notebook / Google Colab.

### 🚀 Methodology
1.  **Data Loading:** Loaded the dataset to understand the structure and feature types.
2.  **Exploratory Data Analysis (EDA):**
    * Used **Pairplots** to visualize the relationships between features and how different species cluster together.
    * Generated a **Correlation Heatmap** to see which measurements are most strongly related.
3.  **Preprocessing:**
    * Separated features (X) and target labels (y).
    * Split the dataset into Training (80%) and Testing (20%) sets.
4.  **Model Building:**
    * Trained a Classification algorithm (e.g., **K-Nearest Neighbors (KNN)**, **Logistic Regression**, or **Support Vector Machine (SVM)**).
5.  **Evaluation:**
    * Calculated the **Accuracy Score** to measure performance.
    * Generated a **Confusion Matrix** to visualize true positives vs. misclassifications.
    * Printed a detailed **Classification Report** (Precision, Recall, F1-Score).

### 📈 Key Results
* The model achieved high accuracy in distinguishing between the three species.
* *Setosa* was the easiest species to identify due to its distinct petal measurements.
* *Versicolor* and *Virginica* showed some overlap but were successfully separated by the model.

### 🔗 Project Link
* **Repository:** [https://github.com/Faizanakacoder/IRIS-FLOWER-CLASSIFICATION](https://github.com/Faizanakacoder/IRIS-FLOWER-CLASSIFICATION)

### 👤 Author Information
* **Name:** Faizan Firoz Shah
* **Internship:** CodSoft Data Science Intern
* **Batch:** January 2026
* **Internship ID:** CS11NY482650
  
