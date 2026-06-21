# ⭐ Star Classification using Machine Learning

## 📌 Project Overview

This project focuses on classifying celestial objects into different classes (Stars, Galaxies, and Quasars) using Machine Learning techniques.

The project includes a complete data science pipeline starting from data exploration and preprocessing, through feature selection and class balancing, and ending with training and evaluating multiple machine learning models.

---

## 🎯 Objectives

- Analyze astronomical data.
- Clean and preprocess the dataset.
- Detect and handle outliers.
- Balance classes using SMOTE.
- Select the most important features.
- Train and evaluate different machine learning models.
- Compare model performance before and after feature selection.

---

## 📂 Dataset

Dataset: **Star Classification Dataset**

The dataset contains astronomical observations with features such as:

- u
- g
- r
- i
- z
- redshift
- Other observational attributes

Target Variable:

- Star
- Galaxy
- Quasar

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset inspection
- Statistical summary
- Class distribution visualization
- Missing values detection
- Duplicate records detection
- Invalid values detection
- Feature distributions
- Correlation analysis
- Outlier detection using:
  - Boxplots
  - IQR Method
  - Local Outlier Factor (LOF)

---

## 🧹 Data Preprocessing

### 1. Data Cleaning

- Removed duplicate rows.
- Replaced invalid values (-9999) with NaN.
- Filled missing numerical values using the median.
- Filled missing categorical values using the mode.

### 2. Label Encoding

Converted target labels into numerical values using LabelEncoder.

### 3. Train-Test Split

- 70% Training Data
- 30% Testing Data

### 4. Class Balancing

Applied **SMOTE (Synthetic Minority Over-sampling Technique)** to balance class distribution.

### 5. Feature Scaling

Used **StandardScaler** to standardize features.

---

## 📊 Feature Selection

Feature importance was calculated using:

- Random Forest Feature Importance

The most relevant features were selected to improve model performance and reduce complexity.

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

### Logistic Regression

- Before Feature Selection
- After Feature Selection

### Random Forest

- Before Feature Selection
- After Feature Selection

### K-Nearest Neighbors (KNN)

- Before Feature Selection
- After Feature Selection

---

## 📈 Evaluation Metric

The primary evaluation metric used was:

- Accuracy Score

Model performances were compared before and after feature selection.

---

## 📉 Visualizations

The project includes several visualizations:

- Class Distribution
- Histograms
- Correlation Heatmap
- Outlier Detection Boxplots
- Accuracy Comparison Charts
- Performance Heatmaps

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn (SMOTE)

---

## 📁 Project Structure

```
├── star_classification.ipynb
├── star_classification.csv
├── README.md
```

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/star-classification-ml.git
```

### 2. Install Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

### 3. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
star_classification.ipynb
```

---

## 📌 Key Learning Outcomes

- Data Cleaning and Preparation
- Exploratory Data Analysis (EDA)
- Outlier Detection
- Feature Engineering
- Feature Selection
- Class Imbalance Handling using SMOTE
- Model Training and Evaluation
- Performance Comparison and Visualization

---

## 👩‍💻 Author

**Mariam Montasser**

Computer Science Student

GitHub: https://github.com/your-username

---

## ⭐ If you found this project useful, don't forget to star the repository!
