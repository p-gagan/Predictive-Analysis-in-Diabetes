# 🧠 Predictive Analysis in Diabetes

This repository contains a complete end-to-end machine learning pipeline for predicting diabetes using logistic regression on the Pima Indians Diabetes Dataset.

[🔗 View Notebook on GitHub](https://github.com/p-gagan/Predictive-Analysis-in-Diabetes)

---

## 📌 Project Objective

To build a supervised machine learning model that predicts whether a person is diabetic based on medical attributes such as glucose level, blood pressure, BMI, age, etc.

---

## 🔍 Dataset Overview

- **Source**: Pima Indians Diabetes Database
- **Samples**: 768
- **Features**: 8 (plus target)
- **Target**: `Outcome` (0: Non-diabetic, 1: Diabetic)

---

## 🛠️ Workflow

### 1. Data Preprocessing
- Handled missing and zero values
- Explored dataset shape, types, and statistics
- Replaced outliers using IQR method
- Standardized features using `StandardScaler`

### 2. Exploratory Data Analysis (EDA)
- Correlation matrix and heatmap
- Distribution plots (histograms + KDE)
- Boxplots for visualizing outliers

### 3. Handling Class Imbalance
- Applied **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset

### 4. Model Building
- Trained **Logistic Regression** using `scikit-learn`
- Evaluated using accuracy, classification report (precision, recall, F1-score)

### 5. Model Evaluation
- Accuracy: ~77%
- Good class separation after SMOTE
- Visual evaluation through classification report

### 6. Saving Model
- Serialized the model using `pickle` for reuse/deployment

---

## 📊 Evaluation Metrics

| Metric         | Score  |
|----------------|--------|
| Accuracy       | 77.08% |
| Precision      | 0.69   |
| Recall         | 0.78   |
| F1-Score       | 0.73   |

---

## 📂 Folder Structure

📁 Predictive-Analysis-in-Diabetes
│
├── 📜 notebook.ipynb # Complete Jupyter notebook
├── 📈 plots/ # EDA and boxplot images
├── 📦 classification_model.pkl # Saved ML model
└── 📄 README.md # This file

---

## 💻 Technologies Used

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- imbalanced-learn (SMOTE)
- Pickle

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/p-gagan/Predictive-Analysis-in-Diabetes.git
   cd Predictive-Analysis-in-Diabetes

2. pip install -r requirements.txt
3. jupyter notebook
4. Run the notebook: notebook.ipynb

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change or improve.

📬 Contact
Gagan [p-gagan]
📧[ LinkedIn Profile](https://www.linkedin.com/in/p-gagan)
🔗 [GitHub](https://github.com/p-gagan/)

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

---

Let me know if you'd like a `requirements.txt` or to auto-generate badges (build passing, license, etc.)!

