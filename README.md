# 🚀 Shuttle System Condition Classification using Machine Learning

## 📌 Overview

This project focuses on classifying **Space Shuttle system operating conditions** based on numerical sensor measurements using **Machine Learning**.

The dataset contains multiple sensor readings collected from shuttle operations. Since interpreting raw sensor values manually can be difficult, this project applies a **Decision Tree classification model** to automatically identify the current system condition.

The goal is to assist operational monitoring and improve understanding of shuttle behavior through data-driven analysis.

---

## 📊 Dataset
* Dataset: Shuttle System Sensor Dataset (shuttle.csv)

### Features

* **A1** → Time / sensor acquisition sequence
* **A2 – A9** → Numerical values from shuttle sensors
* **class** → Target label representing shuttle operating condition

Target classes:

1. Rad Flow
2. Fpv Close
3. Fpv Open
4. High
5. Bypass
6. Bpv Close
7. Bpv Open

---

## 🎯 Objectives

* Explore and understand shuttle sensor patterns
* Build a machine learning model for shuttle condition classification
* Predict shuttle operational state from unseen sensor values
* Evaluate model performance and identify possible improvements

---

## ⚙️ Methodology

### 1. Exploratory Data Analysis (EDA)

* Inspect dataset structure
* Analyze missing values
* Understand class distribution
* Visualize sensor characteristics

### 2. Data Preprocessing

* Handle missing values
* Prepare numerical features
* Balance classes using oversampling

### 3. Feature Selection

* Use all available sensor features (A1–A9)

### 4. Classification (Supervised Learning)

Algorithm implemented:

* **Decision Tree (CART)**
* Splitting criterion: **Gini Impurity**

### 5. Model Evaluation

* Analyze classification performance
* Observe strengths and limitations
* Identify opportunities for future optimization

### 6. Graphical User Interface

Simple **Tkinter GUI** to allow users to input sensor values and obtain predicted shuttle conditions.

---

## 🧠 Key Features

* Sensor-based shuttle condition prediction
* Decision Tree implementation for multi-class classification
* Data preprocessing and imbalance handling
* Interactive GUI for easier usage
* End-to-end ML workflow:

  * EDA
  * Preprocessing
  * Training
  * Evaluation
  * Deployment interface

---

## 📈 Results

* Successfully classified shuttle operating conditions into **7 classes**
* Decision Tree effectively learned patterns from numerical sensor inputs
* Dataset imbalance handling improved training quality
* Future improvements may include:

  * Better missing value strategies
  * Ensemble approaches such as **Random Forest**

---

## 🛠️ Tech Stack

### Machine Learning

* Python
* NumPy
* Pandas

### Visualization

* Matplotlib
* Seaborn

### Interface

* Tkinter

### Environment

* Jupyter Notebook

---

## 🚀 How to Run

```bash
# Clone repository
git clone https://github.com/wahyuayesha/Shuttle-System.git

# Open project
cd Shuttle-System

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Launch Jupyter Notebook
jupyter notebook

# Open and run
shuttle_classification.ipynb
```

---
