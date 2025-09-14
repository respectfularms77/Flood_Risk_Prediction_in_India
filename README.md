# 🌊 Flood Risk Prediction in India

## 📌 Project Overview
This project focuses on **Flood Risk Prediction** as part of the *Climate Risk and Disaster Management* domain.  
Flooding has become one of the most critical natural disasters, especially in regions like India, where heavy rainfall and rising river levels often lead to devastating impacts on lives and infrastructure.  
The objective of this project is to explore, analyze, and build a foundation for predicting flood risks using historical data.

---

## 📂 Dataset
- Source: [Kaggle – Flood Prediction Dataset for India](https://www.kaggle.com/datasets/s3programmer/flood-risk-in-india)  
- The dataset includes rainfall, river water levels, and other related environmental parameters that influence flood occurrences.

---

## 🛠️ Methods and Tools Used
- **Programming Language**: Python 🐍  
- **Libraries**:  
  - `numpy`, `pandas` – Data handling and preprocessing  
  - `matplotlib`, `seaborn` – Data visualization  
  - `sklearn` – Machine Learning models & feature selection  
- **Platform**: Google Colab / Jupyter Notebook  

---

## 🔍 Week 1 Progress
- Imported all necessary libraries  
- Loaded the dataset  
- Performed initial data exploration using:  
  - `df.info()`  
  - `df.describe()`  
  - `df.isnull().sum()`  
  - `df.head()`  

---

## 🔍 Week 2 Progress
### 📊 Exploratory Data Analysis (EDA)
- **Univariate Analysis**  
  - Distribution plots for numerical variables  
  - Count plots for categorical variables  

- **Bivariate Analysis**  
  - Boxplots & barplots comparing features with flood occurrence  

- **Multivariate Analysis**  
  - Correlation heatmap  
  - Pairplots for feature relationships  

### 🔧 Data Transformation
- One-hot encoding for categorical variables (`Land Cover`, `Soil Type`)  
- Label encoding for binary categorical variables (`Infrastructure`, `Historical Floods`)  
- Feature scaling using `StandardScaler` for numerical features  

### 🔍 Feature Selection
- **Correlation Analysis** – Checked relationships with target variable  
- **Chi-Square Test** – Ranked categorical features by importance  
- **Random Forest Importance** – Identified top contributing features  

---

## 📌 Deliverables
- Week 1 Jupyter Notebook (`.ipynb`) uploaded  
- Week 2 Jupyter Notebook (`.ipynb`) uploaded
- Week 3 Jupyter Notebook (`.ipynb`) uploaded
- Dataset uploaded to the repository  
- Link to access the Trained model - https://drive.google.com/file/d/14yEKNLFxONsklovRS9J8qO_6lpLF4KmR/view?usp=drive_link
---
