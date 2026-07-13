# 🏨 Hotel Booking Demand Data Cleaning & Preprocessing

> **A professional end-to-end data cleaning and preprocessing project built using Python and Pandas to transform raw hotel booking data into a high-quality, analysis-ready dataset suitable for Business Intelligence, Machine Learning, and Data Analytics applications.**

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 📖 Project Overview

Real-world datasets are rarely clean. Missing values, inconsistent formats, duplicate records, and outliers often reduce the reliability of analytical insights.

This project demonstrates a complete **data preprocessing pipeline** on the **Hotel Booking Demand Dataset**, following industry-standard data cleaning practices to improve data quality and prepare the dataset for further analysis and visualization.

The project showcases practical skills in:

- Data Cleaning
- Data Wrangling
- Feature Engineering
- Data Quality Assessment
- Documentation
- Python Programming

---

# 🎯 Objectives

✔ Improve overall data quality

✔ Handle missing and inconsistent values

✔ Remove irrelevant information

✔ Standardize categorical variables

✔ Engineer meaningful business features

✔ Detect and treat outliers

✔ Create a reusable, analytics-ready dataset

---

# 📂 Repository Structure

```
Hotel-Booking-Demand-Cleaning/
│
├── 📓 Task1.ipynb
├── 📄 hotel_bookings.csv
├── 📄 sample_hotel_bookings.csv
├── 📄 cleaned_hotel_bookings.csv
├── 📄 sample_cleaned_hotel_bookings.csv
├── 📄 data_dictionary_with_examples.csv
├── 📊 data_dictionary.xlsx
└── 📘 README.md
```

---

# 📁 Project Files

| File | Description |
|------|-------------|
| **Task1.ipynb** | Complete data cleaning and preprocessing workflow |
| **hotel_bookings.csv** | Original raw dataset |
| **sample_hotel_bookings.csv** | Lightweight preview of the raw dataset |
| **cleaned_hotel_bookings.csv** | Final cleaned dataset |
| **sample_cleaned_hotel_bookings.csv** | Preview of cleaned data |
| **data_dictionary_with_examples.csv** | Feature descriptions with sample values |
| **data_dictionary.xlsx** | Professionally formatted data dictionary |

---

# ⚙️ Data Cleaning Pipeline

### 🔹 Missing Value Treatment

- Imputed missing values in **children**
- Filled missing **country** values
- Processed **agent** information
- Removed highly sparse **company** column
- Removed empty unnamed columns

---

### 🔹 Data Standardization

- Standardized hotel names
- Normalized meal categories
- Corrected inconsistent categorical values
- Improved column consistency

---

### 🔹 Feature Engineering

Created several business-friendly features including:

| Feature | Description |
|----------|-------------|
| **arrival_date** | Combined year, month and day into a proper datetime field |
| **total_guests** | Total number of adults, children and babies |
| **stay_length** | Total nights spent in the hotel |
| **is_weekend** | Weekend arrival indicator |

---

### 🔹 Outlier Treatment

Applied the **Interquartile Range (IQR)** method to identify and cap extreme values in:

- Average Daily Rate (ADR)
- Total Guests

---

### 🔹 Documentation

Created a comprehensive **Data Dictionary** containing:

- Column descriptions
- Data types
- Sample values
- Business meaning

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

# 📊 Dataset Information

**Dataset Name**

Hotel Booking Demand Dataset

**Source**

Kaggle

https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

The dataset contains booking information from city and resort hotels, including customer demographics, reservation details, stay duration, booking channels, pricing, and cancellation status.

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Data Wrangling
- Feature Engineering
- Missing Value Imputation
- Outlier Detection
- Data Validation
- Business Data Preparation
- Python Programming
- Pandas
- NumPy

---

# 📈 Workflow

```
Raw Dataset
      │
      ▼
Data Inspection
      │
      ▼
Missing Value Treatment
      │
      ▼
Duplicate Removal
      │
      ▼
Data Standardization
      │
      ▼
Feature Engineering
      │
      ▼
Outlier Detection
      │
      ▼
Clean Dataset
```

---

# 💼 Business Impact

The cleaned dataset can be directly used for:

- Business Intelligence Dashboards
- Customer Segmentation
- Revenue Analysis
- Booking Trend Analysis
- Hotel Performance Monitoring
- Machine Learning Models
- Predictive Analytics

---

# ▶️ Getting Started

Clone this repository:

```bash
git clone https://github.com/Hariomdubey01/Hotel-Booking-Demand-Data-Cleaning.git
```
