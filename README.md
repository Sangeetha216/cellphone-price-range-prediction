<h1 align="center">📱 Cellphone Price Range Prediction</h1>

<p align="center">
  <b>Machine Learning • Multiclass Classification • Mobile Analytics</b>
</p>

<p align="center">
  Predicting the price category of a cellphone from its technical specifications.
</p>

---

## 🔍 The Problem

How can a cellphone's specifications help estimate its market price category?

This project uses historical cellphone specification data to build a Machine Learning model that classifies devices into four price ranges.

The model does not predict the exact selling price. Instead, it determines the appropriate **price category** based on the device's specifications.

---

## 🎯 Prediction Target

| Class | Price Category |
|:---:|---|
| `0` | Low Cost |
| `1` | Medium Cost |
| `2` | High Cost |
| `3` | Very High Cost |

---

## 📱 What Goes Into the Prediction?

The model considers specifications such as:

**Performance**
- RAM
- Processor Cores
- Clock Speed

**Battery & Usage**
- Battery Power
- Talk Time

**Display & Camera**
- Pixel Resolution
- Screen Dimensions
- Front Camera
- Primary Camera

**Connectivity & Features**
- 3G / 4G
- Wi-Fi
- Bluetooth
- Dual SIM
- Touch Screen

**Storage & Build**
- Internal Memory
- Mobile Weight
- Mobile Depth

---

## 🧠 Machine Learning Approach

The project follows a complete classification workflow:

`Data → EDA → Preprocessing → Feature Analysis → Model Building → Tuning → Evaluation → Model Comparison`

Multiple Machine Learning models were trained and evaluated to understand how different algorithms perform on this multiclass classification problem.

Hyperparameter tuning was also performed on selected models to improve their performance.

---

## 📊 Exploratory Analysis

The analysis examines:

- Distribution of cellphone specifications
- Relationships between specifications
- Feature correlations
- Class distribution
- Feature patterns across price categories

The EDA helps identify which cellphone specifications show stronger relationships with the target price range.

---

## 💡 Business Perspective

The model can support a cellphone company in understanding how technical specifications relate to different price categories.

Feature importance analysis can also help identify specifications that have a stronger influence on price-range classification, which can assist in product planning and specification decisions.

---

## 🛠️ Built With

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn` · `XGBoost`

**Environment:** Jupyter Notebook

---

## 📂 Repository

| File | Description |
|---|---|
| `Cellphone Price Range Prediction.ipynb` | Complete analysis and Machine Learning workflow |
| `datasets_11167_15520_train.csv` | Training dataset |

---

## 📌 Project Scope

This project was developed as a Machine Learning practice project focused on **multiclass classification, exploratory data analysis, model comparison, and hyperparameter tuning**.
