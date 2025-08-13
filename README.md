# Feature Engineering – Outlier Detection and Removal

## 📌 Overview
This repository demonstrates different techniques for detecting and removing *outliers* in datasets to improve model performance and data quality.  
We work with real-world datasets such as Bangalore house prices and height data to apply multiple statistical methods.

## 📖 About Outlier Detection
Outliers are data points that deviate significantly from the rest of the dataset.  
They can occur due to errors in measurement, data entry mistakes, or natural variations.  
Removing or handling them appropriately can lead to better model accuracy and stability.

## 🛠 Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## 📂 Projects Included
### 1️⃣ Remove Outliers in Bangalore House Price Data
- *Method:* Min-Max Quantile method
- Identifies and removes extreme values based on a defined quantile range.

### 2️⃣ Remove Outliers in Height Data (Standard Deviation)
- *Method:* Z-score method
- Removes points lying far from the mean based on standard deviation thresholds.

### 3️⃣ Remove Outliers in Height Data (IQR Method)
- *Method:* Interquartile Range
- Removes points lying outside Q1 − 1.5×IQR and Q3 + 1.5×IQR range.
