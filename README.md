# Task 2: Exploratory Data Analysis (EDA)


## 📌 Objective
To explore and understand the given Titanic dataset using descriptive statistics and powerful visualizations. The goal is to uncover patterns, detect anomalies, and gain insights that help inform future modeling tasks.

---

## Key EDA Tasks Covered

### 1. Summary Statistics
- Used `.describe()`, `.info()`, `.isnull().sum()` to understand data structure.
- Calculated mean, median, mode, and standard deviation.

### 2. Univariate Analysis
- Histograms and count plots for numeric and categorical features.
- Boxplots to identify outliers and distribution spread.

### 3. Bivariate & Multivariate Analysis
- Boxplots and violin plots segmented by `Survived` and `Sex`.
- Correlation matrix and heatmap for numeric features.
- Pairplot to observe relationships between key variables.

### 4. Pattern Recognition
- Observed how `Pclass`, `Sex`, `Age`, and `Fare` relate to survival.
- Detected potential outliers in `Fare` and `Age`.

---

## Visual Highlights
- Interactive **Plotly** charts for age and fare distributions.
- Heatmap showcasing **correlations** between numeric variables.
- Seaborn **boxplots with hue** to compare distributions by class and gender.

---

## 💡 Inferences Made
- Females had higher survival rates.
- Higher passenger class (`Pclass = 1`) correlated with better survival.
- Some outliers present in `Fare` and `Age` distributions.
