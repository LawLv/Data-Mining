# Summary

## Overview
The course covers essential topics in data preprocessing, classification, privacy-preserving data mining, and practical machine learning using Python. The coursework emphasizes hands-on assignments with real datasets, performance evaluation, and awareness of data privacy issues.

---

## 📘 Assignment 1: Data Cleaning & Preprocessing

**Objective**: Use Python (pandas in Jupyter Notebook) to clean a medical appointment dataset (`HW1data.csv`), identifying and fixing missing and erroneous entries.

**Key Skills**:
- Handling missing values
- Deduplication & imputation
- Feature engineering (e.g., Delta_Day, Day of Week)
- Data validation and anomaly removal (e.g., negative ages)

**Grading Notes**:
- Each of 9 cleaning steps must be printed and explained
- File naming rules strictly enforced
- Only `.ipynb` format accepted

---

## 📗 Assignment 2: Classification

**Objective**: Train machine learning classifiers on two datasets to achieve high accuracy (>85%) within a 2-minute runtime.

### Task 1: Wine Quality Prediction
- Dataset: `HW2_1_data.csv`
- Target: Wine Quality (labels: 5, 6, 7)
- Features: 11 physicochemical properties (e.g., acidity, alcohol)
- Requirement: Use 2 different classifiers

### Task 2: Synthetic Classification
- Dataset: `HW2_2_data.csv`
- Target: Class Y (based on features X1, X2, X3)
- Requirement: Use 1 classifier

**Grading Notes**:
- Runtime and accuracy thresholds are mandatory
- Print model accuracy
- Include comments for all additional code (e.g., preprocessing)

---

## 📙 Essay: Privacy Protection in Data Mining

**Main Focus**: Survey of methods used to ensure data privacy in data mining, with emphasis on anonymization models and evaluation metrics.

### Key Concepts:
- **Anonymization Models**:  
  - *k-anonymity*: each record is indistinguishable from at least k-1 others  
  - *l-diversity*: sensitive attributes must be well-represented  
  - *(Į,k)-anonymity*, *t-closeness*: improved variations for privacy assurance

- **Techniques**:
  - Data Distortion (e.g., noise addition, blocking, compression)
  - Secure Multi-party Computation (distributed mining without raw data sharing)
  - Bayesian Reconstruction + EM algorithm
  - Association Rule Hiding

- **Evaluation Metrics**:
  - Data Quality (accuracy, completeness)
  - Performance (runtime, scalability)
  - Privacy Degree (e.g., entropy-based metrics)

---


---

