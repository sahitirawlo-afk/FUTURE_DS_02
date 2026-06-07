# FUTURE_DS_02
# Customer Churn Analysis Dashboard

## 📌 Project Overview
This project presents a comprehensive **Customer Churn Analysis Report** designed to identify key factors influencing customer attrition. By analyzing demographic data, contract types, tenure buckets, and payment methods, this dashboard provides data-driven insights to help improve customer retention strategies and minimize business loss.

The dataset analyzes **178 total customers**, tracking key metrics to pinpoint why and where churn is occurring most heavily.

---

## 📊 Key Metrics & KPI Highlights
* **Total Customers:** 178
* **Churned Customers:** 66
* **Churn Rate:** 37.08% *(Critically High)*

---

## 🔍 Visualizations & Data Breakdown

### 1. Demographics & Risk Segmentation
* **Gender Distribution:** Churn is relatively evenly distributed across genders, with both male and female segments showing similar high-churn behavior.
* **Risk Profile:**
    | Risk Segment | Female | Male | Total Customers |
    | :--- | :---: | :---: | :---: |
    | **Low Risk** | 58 | 54 | 112 |
    | **High Risk (Churned)** | 31 | 35 | **66** |
    | **Total** | **89** | **89** | **178** |

### 2. Contract & Payment Preferences
* **Contract Type:** **100%** of the churned customers (all 66) were on a **Monthly Contract**. Standard long-term contracts show significantly higher retention.
* **Payment Method:** Customers using **UPI** represent the highest volume of churned users, followed by a steep decline in churn among **Debit Card** users, and minimal churn among **Credit Card** users.

### 3. Tenure & Age Trends
* **Tenure Buckets:** Attrition is heavily concentrated in the early stages of the customer lifecycle. Customers with **less than 10 months (`<10`)** of tenure experience the highest churn rate by far.
* **Age Profile:** Churn anomalies and spikes are prominently visible in specific age demographics (tracked across ages 27 to 35), signaling the need for targeted age-group marketing or support.

---

## 💡 Key Insights
* **High Initial Attrition:** Churn rate is at **37.08%**, which signals a critical retention issue early on.
* **The Monthly Contract Trap:** Every single customer who left was on a month-to-month plan, proving that short-term contract structures are highly volatile.
* **Onboarding Vulnerability:** Customers with lower tenure ($<10$ months) are the most likely to leave, indicating a potential gap in early engagement or product onboarding.

---

## 🚀 Strategic Recommendations
* **Optimize the Onboarding Experience:** Implement guided onboarding and check-ins for new customers within their first 10 months to build long-term engagement.
* **Incentivize Long-Term Commitments:** Offer discounts, loyalty rewards, or exclusive perks to migrate volatile monthly contract users to annual or multi-month plans.
* **Payment Method Optimization:** Investigate why UPI users churn at higher rates (e.g., failed auto-renewals, transaction friction) and promote auto-pay setups via Credit/Debit cards to increase billing stability.

---

## 🛠️ Tech Stack Used
* **BI Tool:** Power BI and MS Excel
* **Data Source:** Customer Account & Billing Database

##
* Dashboard picture:https://github.com/sahitirawlo-afk/FUTURE_DS_02/blob/main/Screenshot%202026-06-07%20162546.png
  
