# Coder of Delhi — Delhi Area Data Analysis

## 📌 Project Overview

**Coder of Delhi** is a Python-based data analysis project that explores different areas of Delhi using population, income, crime rate, literacy rate, pollution, area size, and population density data.

The project demonstrates an end-to-end data analysis workflow:

**Data Creation → Data Cleaning → Exploration → Statistical Analysis → Visualization → Insights**

The main goal of this project is to demonstrate practical skills in **Python, Pandas, NumPy, Matplotlib, data analysis, and data visualization**.

---

## 🎯 Business Questions

This analysis explores questions such as:

* Which areas have the highest and lowest crime rates?
* How does average income vary across areas?
* Is there a relationship between income and crime rate?
* Does population affect crime rate?
* Is pollution associated with crime rate?
* How does population density vary across areas?
* Which areas stand out based on the analyzed metrics?

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **JupyterLab**

---

## 📊 Dataset Features

The dataset contains information about different Delhi areas, including:

| Feature              | Description                    |
| -------------------- | ------------------------------ |
| `area`               | Name of the Delhi area         |
| `population`         | Population of the area         |
| `avg_income`         | Average income                 |
| `crime_rate`         | Crime rate                     |
| `literacy_rate`      | Literacy rate                  |
| `area_sq_km`         | Area size in square kilometers |
| `population_density` | Population density             |
| `pollution_index`    | Pollution index                |

Additional features were created during the analysis:

* `income_category`
* `crime_category`
* `pollution_category`
* `crime_normalized`
* `pollution_normalized`
* `population_normalized`
* `crime_rank`

---

## 🔍 Analysis Performed

### 1. Data Cleaning & Inspection

* Checked dataset shape and structure
* Examined data types
* Checked missing values
* Checked duplicate records
* Converted columns to appropriate data types
* Performed descriptive statistical analysis

### 2. Area-Level Analysis

Areas were grouped and compared using aggregate statistics for:

* Population
* Average income
* Crime rate
* Pollution index
* Population density

### 3. Crime Rate Analysis

Crime rate was analyzed using:

* Descriptive statistics
* Distribution analysis
* IQR-based outlier detection
* Crime categorization
* Area-wise comparison
* Crime ranking

### 4. Income Analysis

Income levels were categorized into:

* Low
* Medium
* High

The average crime rate of each income category was then compared.

### 5. Pollution Analysis

Pollution levels were categorized into:

* Low
* Medium
* High

The relationship between pollution category and crime rate was explored.

### 6. Correlation Analysis

Correlation analysis was used to examine relationships between:

* Population and crime rate
* Average income and crime rate
* Pollution and crime rate
* Population density and crime rate

### 7. Normalization

Selected numerical variables were normalized to make their values easier to compare.

### 8. Data Visualization

**Matplotlib** was used to create:

* Histograms
* Box plots
* Bar charts
* Scatter plots
* Correlation heatmaps
* Comparative charts

---

## 📈 Key Findings

### 🏆 Highest Crime Rate

**Civil Lines** had the highest average crime rate among the analyzed areas.

### 📉 Lowest Crime Rate

**Preet Vihar** had the lowest average crime rate among the analyzed areas.

### 💰 Income vs Crime

The correlation between average income and crime rate was approximately **0.04**, indicating an almost negligible linear relationship.

Although high-income areas showed a higher average crime rate than medium- and low-income categories in this dataset, this does **not** establish a causal relationship.

### 👥 Population vs Crime

Population showed a weak-to-moderate negative correlation with crime rate.

### 🌫️ Pollution vs Crime

Pollution showed a weak negative correlation with crime rate.

Higher pollution levels therefore did not necessarily correspond to higher crime rates in this dataset.

### 🏘️ Population Density vs Crime

Population density showed a weak negative relationship with crime rate.

### 📊 Overall Insight

No single numerical factor analyzed in this project strongly explains the variation in crime rate across the selected Delhi areas.

---

## 💡 What This Project Demonstrates

This project demonstrates the ability to:

* Clean and inspect structured data
* Work with Pandas DataFrames
* Perform GroupBy and aggregation
* Create derived analytical features
* Categorize numerical variables
* Detect statistical outliers
* Perform correlation analysis
* Normalize numerical data
* Create meaningful visualizations
* Interpret analytical results
* Communicate findings clearly

---

## ⚠️ Important Note

This project is intended for **data analysis and learning purposes**.

The dataset is used to demonstrate analytical techniques and should **not** be interpreted as official crime, income, pollution, or demographic statistics for Delhi.

Correlation observed in the analysis does not imply causation.

---

## 🚀 Future Improvements

Possible future improvements include:

* Adding a larger real-world dataset
* Building an interactive dashboard
* Adding more advanced statistical analysis
* Creating automated data-cleaning pipelines
* Performing predictive analysis
* Adding additional visualizations

---

## 👨‍💻 Project Purpose

This project was created as a practical demonstration of **Python-based data analysis and visualization skills**.

It represents an end-to-end workflow for turning structured data into meaningful analytical insights.
