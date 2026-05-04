# Food Nutrition Analysis using Machine Learning (From Scratch)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**4th Semester AIML Project** | Built from Scratch

---

## 📋 Project Objective

The main goal of this project was to **understand machine learning algorithms from fundamentals** by implementing them **without using any high-level libraries** like scikit-learn.

I analyzed the USDA Nutrition Dataset containing **335 food items** and built three core ML algorithms from scratch using only NumPy and Pandas.

---

## 🎯 Learning Objectives

- Deep understanding of how ML algorithms work internally
- Hands-on experience with data preprocessing and cleaning
- Implementing Linear Regression, KNN, and K-Means from scratch
- Handling real-world challenges like **class imbalance**
- Critical evaluation of model performance

---

## ✨ Key Features

- Complete data cleaning and preprocessing pipeline
- Linear Regression (from scratch) for calorie prediction
- KNN Classifier (from scratch) for Healthy vs Unhealthy food classification
- K-Means Clustering (from scratch) for unsupervised grouping
- Implemented random oversampling from scratch to handle class imbalance

---

## 📊 Results

### KNN Classification

| Model                    | Accuracy | Precision | Recall   | F1 Score |
|--------------------------|----------|-----------|----------|----------|
| KNN (Imbalanced Data)    | 1.0000   | 1.0000    | 1.0000   | 1.0000   |
| **KNN (Balanced Data)**  | **0.9897** | **0.9756** | **1.0000** | **0.9877** |

- **Linear Regression**: **R² Score = 0.8529**
- **K-Means Clustering**: Successfully formed **3 meaningful clusters**

---

## 🧠 Major Learnings

- Understood the **Accuracy Paradox** — how 100% accuracy can hide complete failure on minority class
- Learned the importance of proper evaluation metrics in imbalanced datasets
- Gained strong conceptual clarity by implementing algorithms from scratch
- Realized how simple techniques like oversampling can significantly improve model performance

---

## 🛠️ Technologies & Constraints

- **Language**: Python
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn
- **Constraint**: All ML models built **from scratch** (No scikit-learn models)

---

## 📁 Project Structure
```bash
Food-Nutrition-Analysis/
├── notebooks/
│   └── Food_Nutrition_Analysis.ipynb          # Main Jupyter Notebook
├── data/
│   └── nutrients_csvfile.csv                  # Dataset
├── README.md
├── requirements.txt
└── .gitignore

```
---
## 🚀 How to Run

- **Clone this repository:**
git clone https://github.com/yourusername/Food-Nutrition-Analysis.git

- **Navigate to the project folder:**
cd Food-Nutrition-Analysis

- **Install dependencies:**
pip install -r requirements.txt

- **Place nutrients_csvfile.csv** inside the data/ folder.

- **Start Jupyter Notebook:**
jupyter notebook notebooks/Food_Nutrition_Analysis.ipynb
---
