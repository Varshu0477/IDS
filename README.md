# 🚀 **Multi-Algorithm Classification Analysis**

## 📌 **Overview**
This project implements multiple classification algorithms and evaluates their performance across different train-test split ratios (**80:20, 70:30, and 60:40**). The results are compiled into a **comparative analysis table**.

---

## 🤖 **Algorithms Implemented**
- 🔹 **AdaBoost**
- 🔹 **CatBoost**
- 🔹 **Decision Tree** 🌳
- 🔹 **Gradient Boosting** ⚡
- 🔹 **K-Nearest Neighbors (KNN)** 🔢
- 🔹 **Kernel Support Vector Machine (KSVM)**
- 🔹 **Linear Discriminant Analysis (LDA)**
- 🔹 **Logistic Regression (LG)**
- 🔹 **LightGBM (LGBM)** 🔥
- 🔹 **Linear Support Vector Machine (LSVM)**
- 🔹 **Multi-layer Perceptron Classifier (MLPC)** 🧠
- 🔹 **Naïve Bayes**
- 🔹 **Quadratic Discriminant Analysis (QDA)**
- 🔹 **Random Forest** 🌲🌲
- 🔹 **XGBoost (XGB)** 🚀

---

## 📊 **Dataset**
- 📂 The dataset is loaded from **Book1.csv**.
- 🏷️ **Categorical features** are encoded using **LabelEncoder**.
- 🔧 **Missing values** are handled using **SimpleImputer** with the **mean strategy**.

---

## 🔄 **Preprocessing Steps**
1️⃣ Load and preprocess the dataset (**handle missing values & encode categorical variables**).
2️⃣ Split the dataset into **training and test sets** with three different ratios:
   - ✅ **80:20**
   - ✅ **70:30**
   - ✅ **60:40**
3️⃣ Standardize features using **StandardScaler**.

---

## 📏 **Model Evaluation Metrics**
For each algorithm and split ratio, the following **performance metrics** are computed:
- ✅ **Accuracy** 📈
- ✅ **Precision** 🎯
- ✅ **Recall** 🔍
- ✅ **F1-Score** 🏆
- ✅ **Confusion Matrix** 📊

---

## 📤 **Output**
- 📝 A **comparative table** summarizing the performance of all models under different train-test split ratios.
- 📁 Results are saved as **`model_comparison_results_5.csv`**.

---

## 🛠️ **Dependencies**
Ensure you have the following Python libraries installed before running the script:
```bash
pip install numpy pandas scikit-learn matplotlib xgboost catboost lightgbm
```

---

## ▶️ **Usage**
Run the script using:
```bash
python IDS.ipynb
```

---

## 📌 **Results**
- 📊 The comparative analysis results are stored in **`model_comparison_results_5.csv`** for further analysis.

---

## 📜 **License**
This project is **open-source** and available under the **MIT License**. 📄

---

## 🤝 **Contributions**
🙌 Feel free to contribute by **improving the code, adding more models, or refining the analysis**.

💡 Suggestions and pull requests are **welcome**!

---

🚀 **Happy Coding!** 🎉
