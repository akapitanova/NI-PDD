# NI_PDD Homework Assignments  

This repository contains multiple homework assignments for the **NI_PDD** course, each focusing on different data preprocessing, machine learning, and regression tasks.  

## 📌 Homework Overview  

### 1️⃣ [Data Validation & Cleaning](./01/01_homework.ipynb)  
- Cleaned the **Metropolitan Museum of Art Open Access** dataset.  
- Performed consistency checks on features such as **Object Name** and **Medium**, identifying discrepancies and proposing cleaning methods.  
- Converted features to appropriate data types (numeric, categorical, datetime).  
- Detected and handled missing data, outliers, and integrity issues across several features.  
- Focused on cleaning the **"Medium"** feature for compatibility with machine learning algorithms.  
- Extracted **physical dimensions** (width, depth, height) from the **"Dimensions"** feature.  

---

### 2️⃣ [Balancing & Binning](./02/Homework-2/02_homework.ipynb)  
- Applied **binning techniques** to selected features and analyzed their impact on classification performance.  
- Used different **balancing techniques** to address class imbalance and improved model performance.  
- Ran multiple **classification tests** with unbalanced and balanced datasets, comparing the results of different balancing methods.  
- Evaluated classification metrics to fine-tune the model's predictive capabilities.  

---

### 3️⃣ [Data Transformation & Dimensionality Reduction](./03/03_homework.ipynb)  
- Focused on transforming features and reducing dimensionality for a linear regression model predicting **house sale prices**.  
- Applied **PCA (Principal Component Analysis)** for dimensionality reduction and assessed the impact of the number of principal components.  
- Compared the performance of the model with **feature subsetting** and **PCA** on the test dataset.  
- Optimized the model to minimize **RMSLE** (Root Mean Squared Logarithmic Error) between predicted and actual sale prices.  

---

## 📂 Repository Structure  
- `01/` - Homework 1: Data validation and cleaning  
- `02/` - Homework 2: Balancing and binning  
- `03/` - Homework 3: Data transformation and dimensionality reduction  
