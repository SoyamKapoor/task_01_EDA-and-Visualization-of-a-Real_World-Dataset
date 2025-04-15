# Titanic Dataset - Exploratory Data Analysis & Visualization

This project performs **Exploratory Data Analysis (EDA)** and visualization on the Titanic dataset to uncover meaningful patterns and insights related to survival rates. The analysis includes data cleaning, handling missing values, outlier detection, feature distribution analysis, correlation exploration, and result visualization using Python libraries like **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 📌 Project Overview

### Objectives:
- Load and explore the Titanic dataset
- Clean the dataset: handle missing values, remove duplicates, detect/manage outliers
- Visualize key categorical and numerical features
- Identify correlations and patterns affecting passenger survival
- Summarize findings through data-driven insights

---

## 🧰 Tools & Libraries Used

- Python 3.12.8
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy (for statistical outlier detection)

---

## 📂 Project Structure

```
task_01_EDA-and-Visualization-of-a-Real_World-Dataset/
│
├── Titanic-Dataset.csv               # Raw dataset file
├── Titanic-Dataset_Imputed.csv       # Cleaned dataset after imputation
├── EDA_main.ipynb                    # Jupyter Notebook with full EDA
├── README.md                         # Project overview and instructions
```

---

## 🚀 How to Run the Notebook

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/task_01_EDA-and-Visualization-of-a-Real_World-Dataset.git
   cd task_01_EDA-and-Visualization-of-a-Real_World-Dataset
   ```

2. **Install Required Packages**
   Make sure you have Python 3.12.8 and Jupyter Notebook installed. You can install the required libraries using pip:

   ```bash
   pip install pandas matplotlib seaborn scipy
   ```

3. **Launch the Notebook**
   ```bash
   jupyter notebook EDA_main.ipynb
   ```

4. **Explore the Analysis**
   - Follow each step in the notebook to see the data loading, cleaning, visualization, and insights process.

---

## 📊 Key Steps in the Analysis

### 1. Load and Inspect Data
- Dataset loaded using Pandas
- Basic structure and data types reviewed

### 2. Data Cleaning
- Handled missing values via **mean imputation**
- Removed duplicate rows
- Identified and discussed outliers using both statistical and visual methods

### 3. Data Visualization
- Created histograms for numerical features (Age, Fare, SibSp, Parch)
- Bar plots for categorical variables like survival
- Correlation heatmap to assess relationships between features

### 4. Insights & Observations
- Passengers in higher classes had higher survival rates
- Fare amount showed a moderate positive correlation with survival
- Age and family relationships had limited influence
- Most numerical features are **right-skewed**

---

## 📌 Conclusion

This analysis highlights key demographic and fare-related factors that influenced survival in the Titanic disaster. The project demonstrates foundational data science skills including cleaning, visualization, and insight extraction from real-world data.

---
