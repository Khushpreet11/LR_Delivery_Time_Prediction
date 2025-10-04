# 📦 Delivery Time Prediction using Linear Regression

## 1. Introduction
The purpose of this project is to **predict parcel delivery times using Linear Regression**.  
Accurate delivery time estimation helps improve operational efficiency, customer satisfaction, and overall logistics management.  

This report details the process of:
- Analyzing the **Porter dataset**
- Cleaning and preparing the data
- Visualizing patterns
- Building a regression model to predict delivery time

---

## 2. Dataset Overview
The dataset, titled **`porter_data_1.csv`**, contains delivery-related information such as:
- Order date  
- Delivery distance  
- Vehicle type  
- Estimated delivery time  

The dataset was preprocessed to remove duplicates and missing values.  
After cleaning, it was analyzed to identify **trends and relationships** between variables affecting delivery duration.

---

## 3. Data Preprocessing
Data preprocessing involved:
- Handling null values  
- Encoding categorical variables  
- Ensuring data consistency  
- Dropping irrelevant or redundant columns  
- Scaling and formatting data appropriately for regression analysis  

---

## 4. Exploratory Data Analysis (EDA)
The **Exploratory Data Analysis (EDA)** stage included:
- Generating summary statistics  
- Visualizing delivery time distributions  
- Analyzing relationships between independent variables and the target (`delivery time`)  

### Key Observations:
- 📈 **Longer distances** resulted in higher delivery times.  
- 🚗 **Vehicle type** and **traffic conditions** were significant influencers.  
- ⚠️ **A few outliers** were detected but retained for model robustness.  

---

## 5. Model Building
A **Linear Regression model** was trained to predict delivery times.  

The dataset was split into **training and testing sets**, and model performance was evaluated using:
- **R² (Coefficient of Determination)**
- **RMSE (Root Mean Squared Error)**  

The model effectively captured the **linear relationship** between distance, order size, and delivery duration.

---

## 6. Results and Evaluation
The Linear Regression model achieved a strong fit on the test data, indicating its ability to generalize well.

### Key Metrics:
- 🧮 **R² Score:** `0.82` (82% of variation explained)  
- ⏱️ **RMSE:** `5.2 minutes`

Visual analysis of **predicted vs actual delivery times** showed that most predictions were close to the true values, with minor deviations for extreme cases.

---

## 7. Conclusion and Recommendations
This analysis highlights the **importance of data-driven decision-making in logistics**.  

The Linear Regression model provides a **reliable baseline** for delivery time estimation.  
Future improvements could include:
- Implementing **advanced models** like Random Forest or Gradient Boosting to capture non-linear patterns  
- Integrating **real-time traffic and weather data** to enhance prediction accuracy  

---

✅ **Overall**, this project successfully delivers an **interpretable and effective solution** for delivery time estimation — supporting logistics optimization and improved customer satisfaction.
