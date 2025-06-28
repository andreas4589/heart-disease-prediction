# 🪰 Heart Disease Prediction with Neural Networks and Tree-Based Models

This repository contains all materials used for a thesis comparing a custom-built Artificial Neural Network (ANN) to Random Forest (RF) and XGBoost models in the prediction of heart disease.

---

## 📁 Contents

* `heart.csv` — Heart disease dataset used for training and evaluation (source: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
* `ANN.ipynb` — Jupyter notebook containing the implementation and evaluation of all models
* `README.md` — This file
<!--*  `thesis files/` - All Typst files
* `thesis files/main.typ` — Source code of the thesis written in Typst
* `thesis files/images/` — Plots and diagrams used in the thesis
* `thesis files/refs.bib` — All citations in BibTeX format
-->
---

## 🧠 Project Overview

This project evaluates whether a manually implemented two-layer Artificial Neural Network (ANN) can match or outperform more advanced tree-based models (Random Forest and XGBoost) in predicting heart disease from clinical data.

The models are trained and compared using 15-fold cross-validation, evaluating six metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC, and Log Loss. Permutation feature importance is also used to interpret which clinical features are most predictive.

---

## ⚙️ How to Use

1. **Clone the repository**:

```bash
git clone https://github.com/andreas4589/heart-disease-thesis.git
cd heart-disease-thesis
```

2. **Open the notebook**:
   Launch `ANN.ipynb` in Jupyter or your preferred IDE.

3. **Install dependencies**:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

4. **Run the notebook** to train models and reproduce the results.

---

<!-- ## 📒 Typst Thesis Compilation

1. Install Typst: [https://typst.app](https://typst.app)
2. Open `main.typ`
3. Compile the file to generate a PDF version of the thesis.
-->
---

## 📊 Dataset Information

The dataset includes features derived from patient records such as:

* Demographic info (e.g., age, sex)
* Clinical test results (e.g., cholesterol, blood pressure)
* ECG findings (e.g., ST slope, resting ECG)
* Chest pain and exercise-induced angina information

The dataset was preprocessed to normalize numeric features and encode categorical variables.

---

## 📋 Citation

If you use this repository or its contents in your work, please cite the thesis or contact the author.

---

## 👨‍💻 Author

**Your Name**
GitHub: [andreas4589](https://github.com/andreas4589)
Email: [a.b.meeldijk@students.uu.nl](mailto:a.b.meeldijk@students.uu.nl)

---
