# CodeAlpha_EDA
Exploratory Data Analysis project for CodeAlpha Data Analytics InternshipExploratory Data Analysis project for CodeAlpha Data Analytics Internship

# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project was completed as part of the **CodeAlpha Data Analytics Internship**.

The objective of this project is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python. The analysis focuses on understanding the dataset, identifying missing values, generating descriptive statistics, creating visualizations, and discovering patterns that influenced passenger survival.

---

## 🎯 Objectives

* Load and explore the Titanic dataset.
* Understand the dataset structure and data types.
* Identify and analyze missing values.
* Generate descriptive statistics.
* Visualize important features and relationships.
* Draw meaningful insights from the data.

---

## 📂 Project Structure

```text
CodeAlpha_EDA/
│
├── data/
│   └── titanic.csv
│
├── images/
│   ├── survival_count.png
│   ├── survival_by_gender.png
│   ├── passenger_class_distribution.png
│   ├── survival_by_class.png
│   ├── age_distribution.png
│   ├── fare_distribution.png
│   └── correlation_heatmap.png
│
├── notebooks/
│
├── eda_analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 🛠️ Technologies Used

* Python 3.14
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📊 Exploratory Data Analysis Performed

The notebook includes the following analyses:

* Dataset Overview
* Dataset Shape and Information
* Missing Value Analysis
* Summary Statistics
* Survival Count Analysis
* Survival by Gender
* Passenger Class Distribution
* Survival by Passenger Class
* Age Distribution
* Fare Distribution
* Correlation Heatmap

---

## 📈 Key Insights

* The dataset contains **891 passengers** and **12 features**.
* Approximately **38%** of passengers survived.
* Female passengers had a significantly higher survival rate than male passengers.
* First-class passengers had better survival rates compared to second- and third-class passengers.
* Most passengers traveled in **Third Class**.
* Most passengers were between **20 and 40 years** old.
* Ticket fares are highly right-skewed, with a few passengers paying exceptionally high fares.
* The **Cabin** column contains a large number of missing values, while **Age** also has missing values that require preprocessing.

---

## 📷 Visualizations

### 1. Survival Count

![Survival Count](images/survival_count.png)

---

### 2. Survival by Gender

![Survival by Gender](images/survival_by_gender.png)

---

### 3. Passenger Class Distribution

![Passenger Class Distribution](images/passenger_class_distribution.png)

---

### 4. Survival by Passenger Class

![Survival by Passenger Class](images/survival_by_class.png)

---

### 5. Age Distribution

![Age Distribution](images/age_distribution.png)

---

### 6. Fare Distribution

![Fare Distribution](images/fare_distribution.png)

---

### 7. Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

---

## 📚 Dataset

**Dataset:** Titanic Passenger Dataset

The dataset contains the following information:

* Passenger ID
* Survival Status
* Passenger Class
* Passenger Name
* Gender
* Age
* Number of Siblings/Spouses
* Number of Parents/Children
* Ticket Number
* Fare
* Cabin
* Port of Embarkation

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/CodeAlpha_EDA.git
```

### 2. Navigate to the project directory

```bash
cd CodeAlpha_EDA
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Run all cells in:

```text
eda_analysis.ipynb
```

---

## 📝 Conclusion

The Exploratory Data Analysis of the Titanic dataset revealed that **gender**, **passenger class**, and **ticket fare** were among the most influential factors associated with passenger survival. Female passengers and those traveling in First Class had considerably higher survival rates than male passengers and passengers in Third Class.

The analysis also identified missing values and provided valuable statistical summaries and visualizations that improve understanding of the dataset. This project demonstrates core EDA techniques that form the foundation for data preprocessing and predictive machine learning.

---

## 🚀 Future Improvements

* Handle missing values using appropriate imputation techniques.
* Detect and treat outliers.
* Perform feature engineering.
* Build machine learning models to predict passenger survival.
* Compare multiple classification algorithms.

---

## 👩‍💻 Author

**Arpitha Gowda T R**

**CodeAlpha Data Analytics Intern**

GitHub: https://github.com/Arpitha-1605

LinkedIn: https://www.linkedin.com/in/arpitha-t-r-921088297?utm_source=share_via&utm_content=profile&utm_medium=member_android
