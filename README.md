# 🕵️‍♀️ Homicide Data Analysis — Python & R Lab Project
This project was developed as part of the *Python and R for Data Science Lab* at **LUISS Guido Carli University** (2023–2024). It focuses on analyzing homicide data in the United States, with a particular emphasis on demographic and geographic patterns in states such as **Texas** and **California**.
I employed a combination of data cleaning, processing, visualization, and statistical modeling techniques to uncover trends related to homicide occurrences, resolution rates, and population-driven insights.

---

## 🎯 Project Objectives

	•	Analyze trends in homicide incidents over time
	•	Investigate demographic characteristics of victims and offenders
	•	Examine geographic disparities and cluster U.S. cities by homicide intensity
	•	Predict victim attributes using logistic regression models
	•	Compare resolution rates of homicides across racial groups

 ---

## 📁 Project Structure
.
├── homicide.py         # Python analysis and city clustering
├── geo_analysis.py     # Optional geospatial analysis in Python
├── R_analysis.R        # R script for demographic trends and modeling
├── us_cities.csv       # Coordinates of major U.S. cities
├── population_usafacts.csv  # U.S. population data by location
├── database.csv        # Main homicide dataset (see download instructions)
└── README.md           # Project documentation

---

## 🧪 Analysis Summary

### 🔵 Python: Geospatial and Clustering Analysis
	•	Merged homicide data with population and geolocation information
	•	Focused on Texas and California to assess per-capita homicide trends
	•	Applied KMeans clustering to categorize cities based on homicide intensity
	•	Created scatterplots to visualize spatial clusters and anomalies
	•	Libraries used: pandas, numpy, matplotlib, seaborn, sklearn, geopandas
 
### 🔴 R: Demographics and Predictive Modeling
	•	Filtered and cleaned data by sex, race, age, relationship, and weapon type
	•	Explored time-based trends using ggplot2 and dplyr
	•	Compared clearance rates of homicides by victim race (Black vs. White)
	•	Built a logistic regression model to predict victim sex
	•	Evaluated model performance using ROC curve (via pROC)
	•	Libraries used: tidyverse, pROC, readr, gridExtra, ggplot2

 ---

## 📦 Installation Requirements
To replicate the analysis, install the following dependencies:
**Python:**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn geopandas
```
**R:** 
install.packages(c("dplyr", "ggplot2", "pROC", "readr", "gridExtra"))

---

## 📚 Dataset
I used the publicly available dataset from Kaggle:
🔗 [Homicide Reports – Murder Accountability Project](https://www.kaggle.com/datasets/murderaccountability/homicide-reports)
Note: Due to file size limitations, the dataset is not included in the repository. Please download it manually and save it as database.csv in your working directory.

---

This project was carried out for academic purposes at LUISS Guido Carli University, Rome (2023).

---

## 📄 License
This work is intended for educational and non-commercial use only. Please refrain from redistributing or republishing without permission.

