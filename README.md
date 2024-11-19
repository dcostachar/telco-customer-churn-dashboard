# Telco Customer Churn Dashboard: Visualizing Data for Retention Solutions

Author: Charlene D'Costa <br />
Date: September 3, 2024 <br />
Coursework for the Analyst Builder: Tableau for Data Visualization course. <br />

[Tableau Dashboard](https://public.tableau.com/app/profile/charlene.d.costa/viz/TelcoCustomerChurnDashboard_17256470761000/TelcoCustomerChurnDashboard) 

# Project Overview

<details>
  <summary>Defining the business problem.</summary>

<br /> Reducing customer churn is essential for businesses, as retaining existing customers is more cost-effective than acquiring new ones. By understanding the key drivers of churn, companies can develop strategies to improve customer satisfaction, retention, and profitability. 

For this project, I used the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) (IBM sample data) from Kaggle to build an interactive dashboard in Tableau that provides a comprehensive view of the factors influencing customer churn in the telecommunications industry. Using the insights gained, I developed actionable recommendations to enable businesses to make data-driven decisions that improve customer satisfaction and retention.

**Business Task:** 

Design a dashboard to: 
- Analyze churn patterns and identify key drivers of customer churn
- Identify at-risk customer segments for targeted interventions
- Produce actionable recommendations to inform focused retention strategies and improve customer loyalty

</details>

# Key Insights & Recommendations

<details>
  <summary>Reporting the results of the analysis and providing recommendations to address the business problem.</summary>

## Customer Account Information

### Tenure vs. Churn

| **Insights**                                                                                         | **Recommendations**                                                                                                       |
|------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| New customers (0-5 years of tenure) show the highest churn rates. Nearly half of these customers churned. | **Welcome offers and perks:** Incentivize new customers with discounts, bonus services, or upgrades during the first year. |
| As tenure increases, churn rates drop significantly. Customers with over 10 years are less likely to churn. | **Personalized offers:** Tailor discounts or exclusive deals for at-risk customers.                                       |
| Customers with 20+ years of tenure have much lower churn rates.                                      | **Proactive customer support:** Provide dedicated support early in the customer lifecycle.                                |
| A slight rise in churn is observed among customers in the 60-65 year range.                         | **Surveys and feedback loops:** Use surveys to identify potential pain points for new customers.                          |

---

### Contract Type vs. Churn

| **Insights**                                                                         | **Recommendations**                                                                                           |
|--------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| Month-to-month contracts have the highest churn rate.                                | **Offer discounts for longer contracts:** Encourage 1- or 2-year contracts with discounts or added features. |
| One-year contracts have significantly lower churn rates than month-to-month plans.   | **Offer transitional plans:** Allow easy upgrades to longer contracts with trial periods or no-fee cancellations. |
| Two-year contracts have the lowest churn rates.                                      | **Lock-in incentives:** Offer perks to encourage longer commitments.                                        |

---

### Payment Method vs. Churn

| **Insights**                                                                                     | **Recommendations**                                                                                             |
|--------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| Customers using electronic cheques have the highest churn rate, significantly higher than others. | **Simplify payment experience:** Offer digital wallets or auto-pay to improve satisfaction with payment processes. |

---

## Customer Demographics

### Senior Citizen vs. Churn

| **Insights**                     | **Recommendations**                                                                           |
|----------------------------------|----------------------------------------------------------------------------------------------|
| Senior citizens have a higher churn rate compared to non-seniors. | **Dedicated support:** Offer tailored services and resources to address senior-specific needs. |

---

### Partner vs. Churn

| **Insights**                                   | **Recommendations**                                                                                          |
|-----------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| Customers without partners have a higher churn rate. | **Community-building initiatives:** Create programs that foster a sense of belonging to reduce churn.          |

---

### Dependents vs. Churn

| **Insights**                                   | **Recommendations**                                                                                          |
|-----------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| Customers without dependents have a higher churn rate. | **Family-oriented promotions:** Offer promotions or services attractive to customers with dependents.          |

---

## Services Subscribed

### Phone Service vs. Churn

| **Insights**                     | **Recommendations**                                                                                 |
|----------------------------------|----------------------------------------------------------------------------------------------------|
| Customers without phone service have a higher churn rate. | **Bundled offerings:** Promote bundled packages with discounted rates to encourage phone service adoption. |

---

### Internet Service vs. Churn

| **Insights**                     | **Recommendations**                                                                             |
|----------------------------------|------------------------------------------------------------------------------------------------|
| Customers without internet service have a higher churn rate. | **Promote internet service:** Highlight the benefits and affordability of adding internet services. |

</details>

