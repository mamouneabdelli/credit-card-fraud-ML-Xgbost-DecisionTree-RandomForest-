<div align="center">

# 🛡️ Credit Card Fraud Detection

**Detecting fraudulent transactions using state-of-the-art Machine Learning**

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=for-the-badge&logo=xgboost&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)

</div>

---

## 📌 Overview

Credit card fraud detection is a critical real-world machine learning challenge. Fraud cases are **rare**, making this a highly **imbalanced classification** problem — and exactly the kind of task where smart ML pipelines make a real difference.

This project trains and compares three powerful classification algorithms to distinguish between:

| Label | Meaning |
|-------|---------|
| `0` | ✅ Legitimate Transaction |
| `1` | 🚨 Fraudulent Transaction |

---

## 🧠 Algorithms

### 🌿 Decision Tree
A simple, interpretable model using tree-based split rules. Great as a baseline and easy to visualize.

### 🌲 Random Forest
An ensemble of decision trees trained on random subsets of the data. Reduces overfitting and improves generalization.

### ⚡ XGBoost
A highly optimized gradient boosting framework. Delivers top-tier performance on tabular data and handles class imbalance well.

---

## 📊 Dataset

- **Source:** [Kaggle — Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size:** 284,807 transactions
- **Fraud rate:** ~0.17% (highly imbalanced)
- **Features:** 30 anonymized numerical features (V1–V28, Time, Amount) + target column `Class`

> ⚠️ The dataset is **not included** in this repository. Download it from Kaggle and place it in `dataset/creditcard.csv`.

---

## 🗂️ Project Structure

```
credit-card-fraud-ML/
│
├── 📁 dataset/
│   └── creditcard.csv          # Kaggle dataset (not tracked by Git)
│
├── 📁 notebooks/
│   └── preprocessing.ipynb     # Data exploration & preprocessing
│
├── 📁 models/                  # Saved trained models
│
├── 📁 results/                 # Evaluation metrics & plots
│
├── 📄 requirements.txt         # Python dependencies
└── 📄 README.md
```

---

## ⚙️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/credit-card-fraud-ML.git
cd credit-card-fraud-ML

# 2. Install dependencies
pip install -r requirements.txt

# 3. Add the dataset
# Download creditcard.csv from Kaggle and place it in dataset/
```

---

## 🚀 Usage

Open and run the Jupyter notebook:

```bash
jupyter notebook notebooks/preprocessing.ipynb
```

The notebook covers:
- Exploratory Data Analysis (EDA)
- Handling class imbalance (SMOTE / undersampling)
- Training Decision Tree, Random Forest, and XGBoost
- Evaluating with Accuracy, Precision, Recall, F1-Score, and AUC-ROC

---

## 📈 Model Comparison

| Model | Precision | Recall | F1-Score | AUC-ROC |
|-------|-----------|--------|----------|---------|
| Decision Tree | — | — | — | — |
| Random Forest | — | — | — | — |
| XGBoost | — | — | — | — |

> 📝 Results will be filled in after training. See `results/` for detailed reports.

---

## 🔑 Key Concepts

- **Imbalanced Data** — Fraud is rare; naive models will simply predict "legitimate" every time. Techniques like SMOTE, class weighting, or undersampling are used to address this.
- **Evaluation Metrics** — Accuracy alone is misleading here. F1-Score and AUC-ROC are more meaningful for imbalanced classification.
- **Ensemble Methods** — Random Forest and XGBoost both outperform single decision trees by combining multiple weak learners.

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
xgboost
imbalanced-learn
matplotlib
seaborn
jupyter
```

Install all at once:

```bash
pip install -r requirements.txt
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">


⭐ **Star this repo if you found it useful!** ⭐

</div>
