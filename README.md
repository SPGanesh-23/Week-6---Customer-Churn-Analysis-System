# **Customer Churn Analysis**  
*Exploratory Data Analysis (EDA) & Behavioral Insights using Synthetic Customer Data*

---

## **Overview**
Customer churn is one of the most critical challenges faced by businesses such as banks, telecom companies, and online subscription platforms. When customers stop using a service, organizations experience revenue loss and increased costs in acquiring new customers.

This project addresses the need for automated churn analysis by generating and analyzing a large synthetic dataset of 100,000 customers.

By simulating real-world customer attributes, the system identifies patterns, detects high-risk churn segments, and provides data-driven insights to help businesses improve customer retention strategies while maintaining data privacy.

The workflow includes:

- Large-Scale Data Generation: Creating 100,000 synthetic customer records.
- Data Cleaning: Handling missing values, verifying data types, and encoding categorical variables.
- Churn Classification: Identifying customers likely to leave the service.
- Behavioral Analysis: Comparing churn patterns across age, gender, tenure, and activity status.
- Advanced Visualization: Using charts and heatmaps to understand relationships between variables.

---

## **Dataset**
Source: Synthetic dataset generated using Python
Description: Contains customer demographic and financial attributes such as Age, Balance, Credit Score, and Activity Status.

Dataset Features

- Customer_ID
- Age
- Gender
- Tenure
- Balance
- CreditScore
- EstimatedSalary
- NumOfProducts
- IsActiveMember
- Churn

The dataset simulates real-world customer behavior data for 100,000 customers.

---

## **Objectives**
1. Synthetic Simulation: Generate a large and realistic customer dataset that mimics real-world business environments.
2. Statistical Profiling: Calculate mean, median, mode, and standard deviation for customer attributes.
3. Churn Identification: Detect customers with high probability of leaving.
4. Behavior Analysis: Study relationships such as:
    Age vs Churn
    Balance vs Churn
    Credit Score vs Churn
    Tenure vs Churn
5. Visual Insights: Use charts and heatmaps to identify churn patterns and trends.
---

## **Project Highlights**

### **1. Data Generation**
- Generation: 100,000 synthetic customer records created using NumPy and Pandas.
- Simulation: Real-world banking and telecom scenarios replicated through controlled data distributions.
- Cleaning: Missing values checked and categorical data encoded properly.

### **2. Exploratory Data Analysis (EDA)**
- Customer Profiling: Distribution of age, balance, and credit score.
- Churn Segmentation: Identification of high-risk and low-risk customers.
- Activity Analysis: Comparison between active and inactive members.
- Product Usage Study: Customers with fewer products show higher churn probability.
- EDA helps understand customer behavior and churn patterns.

### **3. Visualization**
The project includes:

- Bar Charts: Churn distribution across gender and activity status.
- Pie Charts: Percentage of churn vs non-churn customers.
- Histograms: Distribution of balance and credit score.
- Scatter Plots: Balance vs churn and credit score vs churn.
- Box Plots: Detecting outliers in salary and balance.
- Heatmaps: Correlation between all customer attributes.
 
Visualizations make business insights easy to understand and interpret.

---

## **Tools and Technologies**
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook
- CSV File Storage

---

## **Results**

### **Key Findings**
- Churn Distribution: Approximately 20–25% of customers were classified as churn in the synthetic dataset.
- Age Trend: Younger customers showed slightly higher churn due to lower tenure.
- Credit Score Impact: Customers with low credit scores had a higher probability of churn.
- Activity Status: Inactive members were more likely to leave the service.
- Product Usage: Customers using only one product showed higher churn rates.
- Balance Influence: High-balance customers were less likely to churn.

### **Interpretation**
- Customer Retention Strategy: Businesses can focus on inactive and low-credit-score customers.
- Predictive Indicators: Tenure, activity status, and product usage are strong churn indicators.
- Data-Driven Decisions: EDA helps companies improve marketing and retention strategies.
- Synthetic Data Advantage: Allows safe experimentation without compromising real customer data.

The structured EDA approach improves clarity, analytical depth, and business decision-making capability.
---

## **Author**
**Shree Pranava Ganesh**  
Student at Kamaraj College
Thoothukudi, Tamil Nadu
