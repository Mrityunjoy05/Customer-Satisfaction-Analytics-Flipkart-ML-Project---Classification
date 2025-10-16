# Flipkart Customer Satisfaction Analytics – Machine Learning

## Project Summary

In the competitive **e-commerce** industry, **customer satisfaction** plays a crucial role in maintaining **brand loyalty** and driving **long-term growth**. This project analyzes **85K+ Flipkart customer interactions** to identify **key factors** influencing **Customer Satisfaction (CSAT) scores**. Using **advanced machine learning techniques**, the project **predicts satisfaction levels** and provides **actionable insights** to enhance **support performance** and **response quality**.

## Dataset Overview

The dataset consists of over **85,000 customer service records** from Flipkart’s **support channels**, including **satisfaction metrics**. Key attributes include:

* **Interaction details**: Channel, Category, Sub-category, Issue Reported, Response Times  
* **Customer and order information**: Order ID, Product Category, City, Item Price  
* **Agent metrics**: Agent Name, Tenure Bucket, Shift, Supervisor, Manager  

The **target variable** is **CSAT Score (Customer Satisfaction Score)**, representing overall **customer satisfaction** with the service experience.

## Analysis Approach

The project follows a structured **machine learning workflow**:

* **Data Preprocessing**: Cleaned and refined **85K+ records** using **null imputation**, **duplicate removal**, and **feature encoding**.  
* **Feature Engineering**: Created **4+ new attributes** (e.g., **Response Time**, **Agent Workload**) to improve **model interpretability**.  
* **Model Building**: Developed **classification models** (**Decision Tree, Random Forest, XGBoost**) to predict **five CSAT classes**.  
* **Evaluation**: Compared model performance using **Accuracy**, **Precision**, **Recall**, **F1 Score**, and **Weighted ROC-AUC**.

## Model Performance

| Model                   | Accuracy | Precision | Recall  | F1 Score | Weighted ROC-AUC |
|-------------------------|----------|-----------|---------|----------|-----------------|
| Decision Tree (GS)      | 0.8791   | 0.9002    | 0.8791  | 0.8872   | 0.9647          |
| Random Forest (Base)    | 0.9376   | 0.9352    | 0.9376  | 0.9341   | 0.9516          |
| XGBoost (GS)            | 0.9428   | 0.9420    | 0.9428  | 0.9393   | 0.9689          |

**Insights from Performance**:

* **XGBoost (GS)** achieved the **highest overall performance**, making it the **preferred model** for CSAT prediction.  
* **Random Forest** also performed strongly and can serve as a reliable alternative.  
* **Decision Tree**, while simpler, shows slightly lower accuracy and F1 scores but provides interpretable insights into key CSAT drivers.

## Key Outcomes

* Evaluated **85K+ customer interactions** to identify **key CSAT drivers**.  
* Cleaned and refined dataset to ensure **100% reliability**.  
* Achieved **XGBoost accuracy: 94.28%**, **Weighted F1 Score: 0.9393**, **Precision: 0.9420**, and **Weighted ROC-AUC: 0.9689**, delivering **actionable insights** for service improvement.  

## Tools & Technologies

* **Python**: Data analysis and **machine learning**  
* **Pandas, NumPy**: Data preprocessing and **feature engineering**  
* **Scikit-learn, XGBoost**: **Model training and evaluation**  

## Conclusion

This project demonstrates how **machine learning** can be applied to analyze **customer feedback** and **predict satisfaction outcomes**. The derived insights enable Flipkart to **optimize customer service strategies**, **improve response efficiency**, and enhance **overall customer experience**.
