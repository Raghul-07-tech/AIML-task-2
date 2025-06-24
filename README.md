# AIML-task-2
# 📊 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the famous [Titanic dataset](https://www.kaggle.com/c/titanic/data). The goal is to uncover patterns, understand feature relationships, and derive insights useful for modeling and decision-making.

---

## 📁 Dataset

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Format**: CSV
- **Download Link**: [Titanic-Dataset.csv](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## ✅ Project Tasks

### 1. Generate Summary Statistics
- Used `df.describe()` and `df.info()` to get:
  - Mean, std, min, max, quartiles.
  - Data types and missing value counts.
- Median computed using `df.median()`.

### 2. Visualize Distributions
- **Histograms** for numeric features.
- **Boxplots** for detecting outliers and comparing feature spreads.
- Tools used: `matplotlib`, `seaborn`.

### 3. Analyze Feature Relationships
- **Correlation Matrix** with `heatmap` to observe linear relationships.
- **Pairplot** for visualizing feature interactions, with class labels (e.g., `Survived`).

### 4. Identify Patterns, Trends, and Anomalies
- Patterns observed:
  - Survival rates vary by **age**, **sex**, **Pclass**, and **fare**.
- Anomalies spotted:
  - Outliers in `Fare`.
  - Missing values in `Age`, `Cabin`.

### 5. Make Basic Inferences
- **Sex**: Females had higher survival rates.
- **Age**: Younger passengers had higher survival chances.
- **Pclass**: 1st class passengers had better survival odds.
- **Fare**: Passengers who paid more had better outcomes.

---

## 📦 Dependencies

```bash
pip install pandas matplotlib seaborn
