# 📈 Customer Churn Analysis

## Project Overview

This project presents a comprehensive **Customer Churn Analysis** derived from telecommunication customer data. The goal is to identify the primary drivers of customer attrition, quantify their impact, and provide actionable insights for retention strategies. The analysis is visualized through an interactive dashboard to facilitate executive decision-making.

The complete dashboard is broken down into several key pages, covering:
* **Executive Overview:** High-level metrics, top churn reasons, and geographic distribution.
* **Age Groups & Customer Segments:** Analysis of churn rates across different age brackets and customer grouping sizes.
* **Payment Methods & Contract Type:** The influence of payment methods and contract duration on customer retention.
* **Impact of Extra Charges:** Deep dive into how extra data and international charges correlate with churn.
* **Geographic Insights:** State-level churn distribution and correlation with customer service call patterns.

---

## 📊 Dashboard Visuals

Here are the key views from the analysis dashboard.  
Upload your screenshots in the repository inside a folder named `/images`.

### Executive Summary
![Executive Overview](customer%20churn%20analysis%20-%20executive%20overview.PNG)

### Age Groups and Segments
![Age Groups and Segments](customer%20churn%20analysis%20-%20age%20group%20%26%20customer%20segments.PNG)

### Payment Methods and Contract Types
![Payment Methods and Contract Types](customer%20churn%20analysis%20-%20payment%20methods%20%26%20contract%20type.PNG)

### Impact of Extra Charges
![Impact of Extra Charges](customer%20churn%20analysis%20-%20impact%20of%20extra%20charges.PNG)

### Geographic Insights
![Geographic Insights](customer%20churn%20analysis%20-%20geographic%20insights.PNG)


---

## 🔑 Key Findings

### 1. Contract & Payment Influence
* **Contract Type:** The **Month-to-Month** contract type accounts for the largest proportion of churned customers (**51.01%** of the contract distribution for all customers). This indicates a high-risk segment with low commitment.
* **Payment Method:** **Paper Check** is associated with significantly shorter average account lengths for customers on **Monthly** contracts, and the highest proportional churn rate among all payment methods (**55.36%** in the Monthly contract category).

### 2. Extra Charges Impact
* **Data Usage:** Customers with **Less than 5 GB** of data usage who *do not* have an Unlimited Data Plan show a strikingly high churn rate of **34.71%**, compared to 12.31% for those with the unlimited plan. This suggests fixed charges for low-usage, non-unlimited customers are a significant deterrent.
* **International Charges:** Customers with no extra international charges (0 bin) have a churn rate of **27%**, suggesting international charges are not the primary driver for a majority of leavers.

### 3. Top Reasons for Churn
The top three explicitly stated reasons for customer churn are:
1.  **Competitor made better offer.**
2.  **Competitor had better devices.**
3.  **Attitude of support personnel.**

---

## 🛠️ Technology Stack

This project is primarily a data visualization effort. The following tools were likely used:

* **Data Analysis:** Python (Pandas, NumPy) or R for initial data cleaning, transformation, and calculation of metrics (like Churn Rate, ARPU).
* **Visualization/Dashboard:** Tools like Power BI, Tableau, or Google Data Studio were likely used to create the interactive dashboard.
* **Data Source:** Assumed to be a telecommunications customer dataset (not included in this repository).

---

## 🚀 Recommended Actionable Insights

Based on the analysis, the following actions are recommended to mitigate churn:

1.  **Target Month-to-Month (M2M) Customers:** Introduce tiered retention offers (e.g., small discount, minor data increase) exclusively for M2M customers to incentivize a switch to a **One-Year Contract**.
2.  **Review Low-Usage Pricing:** Re-evaluate the pricing structure for non-unlimited plans, especially for customers using **Less than 5 GB** of data, as their high churn rate suggests a poor value perception.
3.  **Customer Service Quality:** Conduct a deep-dive audit and mandatory retraining for support personnel, focusing on soft skills and issue resolution efficiency, to address the **"Attitude of support personnel"** churn reason.
4.  **Competitive Intelligence:** Establish a formal process for tracking and counter-offering against top competitor offers and device promotions.
