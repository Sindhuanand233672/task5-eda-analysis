# Task 5 – Exploratory Data Analysis (EDA)

## 📌 Objective
The objective of this task is to perform **Exploratory Data Analysis (EDA)** on a dataset in order to understand the data structure, identify patterns, detect missing values, and extract meaningful insights using statistical and visual techniques.

---

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset Used
- **Titanic Dataset**

The dataset contains passenger information such as age, fare, class, gender, and survival status.

---

## 🔍 EDA Steps Performed

### 1️⃣ Data Understanding
- Loaded the dataset using Pandas
- Used `info()`, `describe()`, and `value_counts()` to understand data types and distributions

### 2️⃣ Missing Value Analysis
- Identified missing values using `isnull().sum()`
- Observed missing data in Age and Cabin columns

### 3️⃣ Univariate Analysis
- Histogram for Age distribution
- Boxplot for Fare distribution

### 4️⃣ Bivariate Analysis
- Scatter plot between Age and Fare

### 5️⃣ Multivariate Analysis
- Pairplot to analyze relationships between multiple variables
- Correlation heatmap to understand feature relationships

---

## 📈 Key Insights
- The dataset contains missing values in Age and Cabin columns
- Survival rate is influenced by passenger class and fare
- Higher fare passengers had better survival chances
- Age does not show a strong correlation with survival
- No severe multicollinearity among numerical features

---

## 📁 Files Included
| File Name | Description |
|---------|-------------|
| `Task5_EDA_Titanic.ipynb` | Jupyter Notebook with EDA code and observations |
| `Task5_EDA_Titanic_Report.pdf` | PDF report containing visuals and findings |
| `README.md` | Project documentation |

---

## ✅ Conclusion
This exploratory data analysis provided valuable insights into the Titanic dataset and helped in understanding important factors affecting passenger survival.

---


