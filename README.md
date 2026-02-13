<h1 align="center">🛒 ShopSmart - Purchase Prediction System</h1>
<p align="center">
  <strong>Supervised Machine Learning Project for E-commerce Conversion Prediction</strong>
</p>

---

## 🚀 About The Project

ShopSmart is a supervised machine learning project designed to predict whether a visitor to an e-commerce website will complete a purchase.

Using behavioral session data, this system helps businesses:
- Improve marketing strategies
- Identify high-intent customers
- Reduce revenue loss
- Optimize targeting efforts

---

## 🎯 Project Objective

To build a **Decision Tree-based classification model** that predicts:

- ✅ Purchase (Revenue = True)
- ❌ No Purchase (Revenue = False)

Since the dataset is **imbalanced**, model performance is evaluated using the **F1-score**, with a benchmark of **0.55**.

---

## 📊 Dataset Overview

The dataset contains **12,330 individual user sessions** collected over one year.

Each session includes numerical and categorical features describing visitor behavior.

### Key Features

| Feature | Description |
|----------|-------------|
| Administrative | Pages related to account management |
| Administrative_Duration | Time spent on admin pages |
| Informational | Informational pages visited |
| Informational_Duration | Time on informational pages |
| ProductRelated | Product pages visited |
| ProductRelated_Duration | Time on product pages |
| BounceRates | Percentage leaving after one page |
| ExitRates | Page exit percentage |
| PageValues | Page value before transaction |
| SpecialDay | Closeness to special events |
| Month | Month of visit |
| OperatingSystems | Visitor OS |
| Browser | Visitor browser |
| Region | Geographic region |
| TrafficType | Traffic source |
| VisitorType | Returning / New / Other |
| Weekend | Weekend visit indicator |
| Revenue | Target variable (Purchase or Not) |

---

## 🧠 Machine Learning Workflow

1️⃣ Data Cleaning & Preprocessing  
2️⃣ Exploratory Data Analysis (EDA)  
3️⃣ Handling Class Imbalance  
4️⃣ Feature Encoding & Scaling  
5️⃣ Train-Test Split  
6️⃣ Decision Tree Model Training  
7️⃣ Pruning to Reduce Overfitting  
8️⃣ Evaluation using F1-score  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  

---

## 📊 Evaluation Metrics

Since the dataset is imbalanced, the primary metric is:

- **F1 Score (Target ≥ 0.55)**

Additional metrics:
- Accuracy
- Precision
- Recall
- Confusion Matrix

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/Ishu335/ShopSmart.git
cd ShopSmart
