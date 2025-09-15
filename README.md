# ❤️ Heart Failure Prediction ML Models

This repository applies various supervised learning algorithms to predict the risk of heart failure, based on the **Heart Failure Prediction** dataset from Kaggle.  
The evaluation focuses primarily on **recall**, to reduce **false negatives**, thus helping to better identify patients who are at risk.

---

## 🚀 Models Used
- Logistic Regression (LR)  
- Random Forest (RF)  
- Support Vector Machine (SVM)  
- Decision Tree (DT)  
- K-Nearest Neighbors (KNN)  

---

## 📚 Dataset

The project uses the **Heart Failure Prediction** dataset from Kaggle:  
[fedesoriano/heart-failure-prediction]  
It contains clinical features and seems designed to predict deaths due to heart failure. :contentReference[oaicite:0]{index=0}

---

## 🎯 Objectives

- Train and compare several classification models.  
- Prioritize **recall** (minimize false negatives) because missing a high-risk patient has serious consequences.  
- Automatically select the best model under that criterion.  

---

## 📂 Project Structure

data/heart.csv
src/Heart_Failure_Prediction.ipynb
requirements.txt

---

## ⚙️ Installation

# Clone the repository
git clone https://github.com/moonmido/Heart-Failure-Prediction-ML-Models.git

# Navigate into the project folder
cd Heart-Failure-Prediction-ML-Models

# Install dependencies
pip install -r requirements.txt

