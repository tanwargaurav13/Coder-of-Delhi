# 🏙️ Coder of Delhi — Delhi Area Data Analysis

## 📌 Project Overview

**Coder of Delhi** is a data analysis project focused on analyzing different areas of Delhi using Python.

The project explores relationships between population, average income, crime rate, literacy rate, pollution index, area size, and population density.

The main objective is to demonstrate practical data analysis skills including data cleaning, aggregation, statistical analysis, categorization, correlation analysis, normalization, and data visualization.

---

## 🎯 Objectives

- Analyze population distribution across Delhi areas
- Study average income across different areas
- Analyze crime rate and identify high/medium/low crime areas
- Explore the relationship between income and crime rate
- Study population density across different areas
- Analyze the relationship between pollution and crime
- Identify areas with the highest and lowest crime rates
- Use statistical techniques to understand the dataset
- Create meaningful visualizations for data-driven insights

---

## 🛠️ Tools & Technologies

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **JupyterLab**

---

## 📊 Dataset Features

The dataset contains information related to different Delhi areas, including:

- `area`
- `population`
- `avg_income`
- `crime_rate`
- `literacy_rate`
- `area_sq_km`
- `population_density`
- `pollution_index`

Additional derived features were created during the analysis, including:

- `income_category`
- `crime_category`
- `pollution_category`
- `crime_normalized`
- `pollution_normalized`
- `population_normalized`
- `crime_rank`

---

## 🔍 Analysis Performed

### 1. Data Cleaning & Inspection

- Checked dataset shape and structure
- Examined data types
- Checked missing values
- Checked duplicate records
- Converted columns to appropriate data types
- Performed basic statistical exploration

### 2. Area-Level Analysis

Areas were grouped and analyzed using aggregate statistics for:

- Population
- Average income
- Crime rate
- Pollution index
- Population density

### 3. Crime Rate Analysis

Crime rates were analyzed using:

- Mean and descriptive statistics
- Distribution analysis
- IQR-based outlier detection
- Crime categorization
- Area-wise crime comparison
- Crime ranking

### 4. Income Analysis

Income levels were divided into three categories:

- Low
- Medium
- High

The average crime rate of each income category was then compared.

### 5. Pollution Analysis

Pollution levels were categorized into:

- Low
- Medium
- High

The relationship between pollution category and average crime rate was explored.

### 6. Correlation Analysis

Correlation analysis was performed to understand relationships between:

- Population and crime rate
- Average income and crime rate
- Pollution and crime rate
- Population density and crime rate

### 7. Normalization

Selected numerical variables were normalized to make their values easier to compare.

### 8. Data Visualization

Matplotlib was used to create:

- Histograms
- Box plots
- Bar charts
- Scatter plots
- Correlation heatmaps
- Comparative charts

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

This indicates that higher pollution levels do not necessarily correspond to higher crime rates in this dataset.

### 🏘️ Population Density vs Crime

Population density showed a weak negative relationship with crime rate.

### 📊 Overall Insight

No single numerical factor analyzed in this project strongly explains the variation in crime rate across the selected Delhi areas.

---

## ⚠️ Important Note

This project is intended for **data analysis and learning purposes**.

The dataset is used to demonstrate analytical techniques and should not be interpreted as official crime, income, pollution, or demographic statistics for Delhi.

Correlation observed in the analysis does not imply causation.

---

## 🚀 Skills Demonstrated

Through this project, the following practical data analysis skills were demonstrated:

- Data Cleaning
- Data Exploration
- Pandas DataFrame Operations
- NumPy Operations
- GroupBy & Aggregation
- Pivot Tables
- Statistical Analysis
- Outlier Detection
- Data Categorization
- Correlation Analysis
- Data Normalization
- Data Visualization
- Analytical Interpretation

---

## 📁 Project Structure

```text
Coder-of-Delhi/
│
├── coder_of_delhi.ipynb
├── README.md
└── dataset/