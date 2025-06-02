# 📊 Telco Customer Churn Analysis

## 📝 Project Description

This project investigates the factors influencing customer churn in a California-based telecommunications company. By analyzing customer demographics, subscription preferences, and behavioral patterns, the goal is to deliver actionable insights that enable data-driven customer retention strategies in an increasingly competitive market.

---

## 📂 About the Dataset

The dataset represents fictional customer data from a U.S.-based telecom company and includes a rich mix of demographic, service usage, and churn-related variables.

### Key Attributes:

- **Customer Demographics**: Gender, city, state, ZIP code, geographic coordinates
- **Subscription Info**: Contract type, payment method, monthly charges
- **Churn Data**: Churn status, churn score, customer lifetime value (CLTV), churn reasons
- **Churn Reasons**: Include dissatisfaction, competition, and relocation

---

## 🧹 Data Preparation

Data was cleaned and transformed using **Power Query Editor**, with key steps including:

- Verified consistency with the source file
- Updated data types for identifiers and numerical columns
- Handled missing values in the *Churn Reason* column (set to `"Unknown"`)

---

## 🧠 Data Modeling

Since the dataset contains a single table, no relationship modeling was required.

---

## 📈 Data Visualization (Power BI)

The Power BI dashboard includes the following interactive pages:

- **Overview Page**: Key metrics and business KPIs
- **Demographics Page**: Analysis by age, gender, and household structure
- **Subscription Page**: Services subscribed to and their churn impact
- **Contract & Payment Page**: Breakdown by contract length, payment type, and billing behavior

## 📸 Dashboard Screenshot

![Dashboard Overview](/images/Overview.png)
![Demographics](/images/Demographics.png)
![Subscription](/images/Subscriptions.png)
![Contract Terms](/images/Contract Terms.png)
---

## 💡 Key Insights

### 🔎 Overview

- **Churn Rate**: `26.54%` (1,869 out of 7,043 customers)
- **Revenue at Risk**: `$456.12K` in monthly losses; `$16.06M` total risk

### 🔄 Top Churn Reasons

- Poor support experiences:
  - "Attitude of support person" – 192 cases
  - "Attitude of service provider" – 135 cases
- Competition-driven:
  - "Competitor offered higher speeds" – 189 cases
  - "Better data plans" / "More attractive offers" – 130–160 cases

### 👥 Demographic Patterns

| Segment           | Churn Rate | Insight                              |
|------------------|------------|--------------------------------------|
| Senior Citizens   | 41.68%     | Highest risk demographic             |
| No Dependents     | 32.55%     | Higher churn than those with dependents |
| No Partner        | 32.96%     | More likely to churn                 |
| Gender (M/F)      | ~26%       | Minimal impact on churn              |

✅ **Conclusion**: Focus retention on seniors and customers without partners or dependents.

### 📦 Service & Subscription Insights

| Service           | Churn (No) | Churn (Yes) | Insight                            |
|------------------|------------|-------------|------------------------------------|
| Tech Support      | 41.64%     | 15.17%      | Support reduces churn              |
| Online Security   | 41.77%     | 14.61%      | Strong churn-prevention feature    |
| Device Protection | 39.13%     | 22.50%      | Adds value and reduces churn       |
| Internet (Fiber)  | 41.89%     | —           | Higher churn vs DSL (18.96%)       |

✅ **Conclusion**: Bundled and value-added services improve retention.

### 💳 Contract & Payment Preferences

| Factor            | High-Risk Segment       | Churn Rate | Insight                                  |
|------------------|--------------------------|------------|------------------------------------------|
| Contract Type     | Month-to-Month           | 42.71%     | Key churn segment                        |
| Billing Method    | Paperless Billing (Yes)  | 33.57%     | Higher churn—tech-savvy segment          |
| Payment Method    | Electronic Check         | 45.29%     | Highest churn—needs further investigation|

---

## 🎯 Recommendations

1. **Targeted Retention Campaigns**  
   Focus on senior citizens, single customers, and short-term contract holders.

2. **Bundle Services Strategically**  
   Promote value-added services like tech support and online security.

3. **Enhance Support Quality**  
   Improve soft-skills training and implement feedback loops.

4. **Encourage Contract Upgrades**  
   Offer early renewal discounts and loyalty incentives.

5. **Optimize Billing & Payments**  
   Improve billing UX and evaluate concerns with electronic checks.

---

## 🛠️ Technologies Used

- **Power BI** – For data visualization and dashboarding  
- **Power Query** – For data cleaning and transformation  

---