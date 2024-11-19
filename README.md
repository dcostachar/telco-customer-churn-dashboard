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
- New customers (0-5 years of tenure) show the highest churn rates. Nearly half of these customers have churned.
- As tenure increases, churn rates drop significantly. Customers with more than 10 years of tenure are less likely to churn.
- Customers with 20+ years of tenure have much lower churn rates, indicating a strong retention trend among long-term customers.
- There is a slight rise in churn for customers in the 60-65 year range, which may warrant further investigation.

**Recommendations**
- **Welcome offers and perks:** During the first year, provide new customers with incentives such as discounts, bonus services, or upgrades to increase their perceived value and commitment to the company.
- **Personalized offers:** Once customers are identified as at-risk, provide tailored offers (discounts, service upgrades, or exclusive deals) to re-engage them and show that the company values their loyalty.
- **Proactive customer support:** Provide dedicated support in the early stages of the customer lifecycle. Frequent check-ins within the first few months can address issues before they lead to churn.
- **Surveys and feedback loops:** Regularly collect feedback from newer customers to identify potential pain points early. Use this data to address common issues that may lead to dissatisfaction and churn.

### Contract Type vs. Churn                                                                      
- Month-to-month contracts have the highest churn rate, with 1,655 out of 3,875 customers leaving.
- Customers with one-year contracts have significantly lower churn rates, with only 166 out of 1,473 leaving. The lowest churn rate is seen in two-year contracts, where only 63 out of 1,710 customers churned, highlighting a strong retention trend associated with longer contracts.

**Recommendations**
- **Offer discounts for longer contracts:** Encourage customers to commit to 1- or 2-year contracts with discounted rates or added features. This can help lock in customers and reduce the likelihood of churn within the early years.
- **Offer Transitional Plans:** Provide an option for month-to-month customers to easily upgrade to a one- or two-year contract, potentially with trial periods or no-fee cancellations within the first few months, reducing friction and making the shift more attractive.
                                                                
### Payment Method vs. Churn                                                                               
- Customers using electronic cheques have the highest churn rate, significantly higher than other payment methods.

**Recommendations**
- **Simplify and Improve Payment Experience:** Ensure that all payment methods are easy to use and hassle-free. Address any common issues faced by cheque users, such as delays or processing problems, and offer convenient alternatives like digital wallets or automatic payments to enhance customer satisfaction and retention.|

### Total Charges / Monthly Charges vs. Churn                                                                                  
- Customers with higher monthly charges (around $80 and above) who have been with the company for a shorter period (indicated by low total charges) show a higher concentration of churn. These are likely month-to-month customers, who tend to churn at higher rates, as indicated by the Contract Type vs. Churn visualization.

**Recommendations**             
- **Implement Gradual Pricing Increases to Reduce Early Churn:** Keep initial costs low for new customers and gradually increase charges over time to recoup the return on investment (ROI).

<br /> 

## Customer Demographics 

### Senior Citizen vs. Churn  
- Senior citizens have a higher churn rate than non-seniors.

**Recommendations**     
- **Dedicated support:** Offer tailored services and resources to address senior-specific needs.

### Gender vs. Churn                             
- The number of male and female customers is almost evenly distributed.
- There does not appear to be a significant difference in churn rates based on gender.

**Recommendations**                                                                                          
- **Focus on high-risk segments:** Rather than creating gender-specific strategies, the company should prioritize its efforts on customer segments with higher churn, such as customers on month-to-month contracts or those with high monthly charges.

### Dependents vs. Churn    
- Customers without dependents have a higher churn rate, with 1,543 churned customers out of 4,933 total.
- Customers with dependents show a significantly lower churn rate, with only 326 churned customers out of 2,110 total.

**Recommendations**                                                                                          
- **Develop Family-Oriented Service Plans:** To encourage more long-term commitments, consider introducing or promoting family-oriented service plans.

<br /> 

## Services Subscribed 

### Tech Support vs. Churn                 
- Customers without tech support have the highest churn rate, with 1,446 out of 3,473 customers churning.
- Customers with tech support have a much lower churn rate, with 310 out of 2,044 customers churning.

**Recommendations**
- **Promote Tech Support Services:** Given the significantly lower churn rate among customers with tech support, the business should actively promote and incentivize tech support packages. Offering these services, especially to customers currently without tech support, can improve retention rates by addressing potential technical issues before they lead to dissatisfaction.
- **Offer Free or Discounted Tech Support for High-Risk Customers:** To target at-risk customers (those without tech support), consider offering limited-time free or discounted tech support as part of retention strategies. This can increase customer satisfaction, reduce technical issues, and lower churn.

</details>

