# Flipkart Customer Satisfaction Analytics – Machine Learning

## Project Summary

In the competitive **e-commerce** industry, **customer satisfaction** plays a vital role in maintaining **brand loyalty** and driving **long-term growth**. This project focuses on analyzing **85K+ Flipkart customer interactions** to identify **key factors** influencing **Customer Satisfaction (CSAT) scores**. Using **advanced machine learning techniques**, the project **predicts satisfaction levels** and provides **actionable insights** to enhance **support performance** and **response quality**.

## Dataset Overview

The dataset contains over **85,000 customer service records** from Flipkart’s **support channels**, and **satisfaction metrics**. It includes key attributes such as **interaction details** (Channel, Category, Sub-category, Issue Reported, Response Times), **customer and order information** (Order ID, Product Category, City, Item Price), and **agent metrics** (Agent Name, Tenure Bucket, Shift, Supervisor, Manager).

The **target variable** is **CSAT Score (Customer Satisfaction Score)**, measuring overall **satisfaction** with the **service experience**.

## Analysis Approach

The project follows a systematic **machine learning workflow**:

* **Data Preprocessing**: Cleaned and refined **85K+ records** using **null imputation**, **duplicate removal**, and **feature encoding**.

* **Feature Engineering**: Created **4+ new attributes** (e.g., **response efficiency**, **complaint frequency**) to improve **model interpretability**.

* **Model Building**: Developed **classification models** (**Logistic Regression, Random Forest, XGBoost**) to predict **five CSAT classes**.

* **Evaluation**: Selected the **best-performing model** using **accuracy**, **Weighted F1**, **Precision**, and **ROC-AUC metrics**.

## Key Outcomes

* Evaluated **85K+ customer interactions** to identify **key CSAT drivers**.
* Refined dataset to **100% reliability** through **cleaning** and **feature engineering**.
* Achieved **93.2% accuracy** and **Weighted F1 Score: 0.929** in **CSAT prediction**.
* Delivered strong performance with **Weighted Precision: 0.93** and **ROC-AUC: 0.94**, offering **actionable insights** for **service improvement**.

## Tools & Technologies

* **Python**: Data analysis and **machine learning**
* **Pandas, NumPy**: Data preprocessing and **feature engineering**
* **Scikit-learn, XGBoost**: **Model training and evaluation**

## Conclusion

This project effectively leverages **machine learning** to analyze **customer feedback** and **predict satisfaction outcomes**. The insights derived enable Flipkart to **optimize customer service strategies**, **improve response efficiency**, and enhance **overall customer experience**.
