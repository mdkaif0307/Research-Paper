# 🌱 Prediction of Land Suitability for Crop Cultivation using Data Analysis and  Machine Learning

## 📌 Overview

This repository contains the implementation and research work for the paper:

**Prediction of Land Suitability for Crop Cultivation Based on Soil and Environmental Characteristics Using Modified Recursive Feature Elimination Technique with Various Classifiers**

The project focuses on predicting the most suitable crop for cultivation by analyzing soil properties and environmental conditions using Machine Learning. A Modified Recursive Feature Elimination (MRFE) technique is used to identify the most important features before training multiple classification models to improve prediction accuracy.

---

## 🎯 Objectives

* Analyze soil and environmental parameters for crop prediction.
* Perform data preprocessing and feature engineering.
* Select the most relevant features using Modified Recursive Feature Elimination (MRFE).
* Train and compare multiple Machine Learning classifiers.
* Evaluate model performance using standard classification metrics.
* Identify the best-performing model for land suitability prediction.

---

## 📊 Dataset Features

The dataset includes various agricultural and environmental attributes such as:

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Soil pH
* Electrical Conductivity (EC)
* Organic Carbon (OC)
* Sulfur (S)
* Zinc (Zn)
* Iron (Fe)
* Copper (Cu)
* Manganese (Mn)
* Boron (B)
* Soil Texture
* Temperature
* Rainfall
* Season
* Crop Label (Target Variable)

---

## ⚙️ Project Workflow

```text
Dataset Collection
        │
        ▼
Data Preprocessing
        │
        ▼
Data Cleaning & Encoding
        │
        ▼
Feature Extraction
        │
        ▼
Modified Recursive Feature Elimination (MRFE)
        │
        ▼
Train-Test Split
        │
        ▼
Machine Learning Models
        │
        ▼
Performance Evaluation
```

---

## 🤖 Machine Learning Models Used

* K-Nearest Neighbors (KNN)
* Naive Bayes
* Decision Tree
* Support Vector Machine (SVM)
* Random Forest
* Bagging Classifier
* Voting Classifier

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* AUC-ROC
* Mean Absolute Error (MAE)
* Log Loss

---

## 🏆 Results

Among all evaluated models, the **Voting Classifier** achieved the highest overall performance with:

* ✅ Accuracy: **100%**
* ✅ Precision: **100%**
* ✅ Recall: **100%**
* ✅ F1-Score: **100%**
* ✅ AUC: **1.000**
* ✅ MAE: **0.000**

This demonstrates the effectiveness of combining MRFE with ensemble learning for accurate crop suitability prediction.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Machine Learning
* Feature Selection (MRFE)

---

## 📂 Repository Structure

```text
├── Dataset/
├── Source Code/
├── Models/
├── Results/
├── Research Paper.pdf
├── requirements.txt
└── README.md
```

---

## 🚀 Future Improvements

* Integrate real-time IoT sensor data.
* Expand the dataset with additional soil and climate conditions.
* Explore advanced ensemble methods such as XGBoost and Gradient Boosting.
* Investigate Deep Learning models for large-scale agricultural prediction.
* Develop a web-based decision support system for farmers.

---

## 📄 Research Publication

This repository accompanies the research paper:

**Prediction of Land Suitability for Crop Cultivation Based on Soil and Environmental Characteristics Using Modified Recursive Feature Elimination Technique with Various Classifiers**

---

## 👨‍💻 Authors

* **Dr. M. Upendra Kumar**
* **Mohammed Kaif**
* **Syed Luqmanuddin**

---

## ⭐ Acknowledgements

This work aims to contribute toward precision agriculture by leveraging Machine Learning techniques to improve crop recommendation accuracy, optimize land utilization, and support sustainable farming practices through intelligent data-driven decision making.
