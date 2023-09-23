**Telecom Customer Churn Prediction**

![](Aspose.Words.c097839a-82c6-424c-bf83-39f873bba53c.001.png)

## **Problem Statement**

The telecom industry is highly competitive, and customer churn is a significant concern. Retaining existing customers is often more cost-effective than acquiring new ones. This case study aims to build a predictive model to identify customers who are likely to churn, allowing the company to take proactive measures to retain them.

The primary objective is to develop a machine learning model that can predict customer churn with high accuracy. The model will use historical data to identify patterns or characteristics of customers who have churned in the past.

**What is Customer Churn?**

Customer churn is defined as when customers or subscribers discontinue doing business with a firm or service.

Customers in the telecom industry can choose from a variety of service providers and actively switch from one to the next. The telecommunications business has an annual churn rate of 15-25 percent in this highly competitive market.

Individualized customer retention is tough because most firms have a large number of customers and can't afford to devote much time to each of them. The costs would be too great, outweighing the additional revenue. However, if a corporation could forecast which customers are likely to leave ahead of time, it could focus customer retention efforts only on these "high-risk" clients. The ultimate goal is to expand its coverage area and retrieve more customer loyalty. The core to success in this market lies in the customer itself.

Customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers.

**To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.**

To detect early signs of potential churn, one must first develop a holistic view of the customers and their interactions across numerous channels, including store/branch visits, product purchase histories, customer service calls, Web-based transactions, and social media interactions, to mention a few.

As a result, by addressing churn, these businesses may not only preserve their market position but also grow and thrive. The more customers they have in their network, the lower the cost of initiation and the larger the profit. As a result, the company's key focus for success is reducing client attrition and implementing an effective retention strategy.

**Findings:**

**1.** The data set includes information about:
- **Customers who left** – the column is called Churn
- **Services that each customer has signed up for** – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- **Customer account information** - how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- **Demographic info about customers** – gender, age range, and if they have partners and dependents

**2. Demographics** - Let us first understand the gender, age range, partner, and dependent status of the customers.

- **Gender Distribution** - About half of the customers in our data set are male while the other half are female.
- **%Senior Citizens** - Only 16.2% of customers are senior citizens and most of the customers are young.
- **Partner and dependent status** - About 50% of the customers have a partner, while only 30% of the total customers have dependents.


**3. Customer Account Information:** Let us now learn about the tenure and contract.                                     

- **Tenure -** A lot of customers are with the company for just the first few months while many are there for above 70 months, this could be because of different types of contracts. Thus based on the contract they are into it could be more/less easier for the customers to stay/leave the telecom company.
- **Contract Type-** Most of the customers are in the month-to-month contract. While there are equal number of customers in the 1 year and 2 year contracts.

1. **Customer service Information-** Let us now look at the distribution of various services used by customers.

- **Categories More Likely to Churn**
1. **Dependents vs. Churn:** Customers without dependents are more likely to churn.
1. **Partner vs. Churn:** Customers who don't have partners are more likely to churn.
1. **Contract vs. Churn:** More Month-to-Month Contract customers opted to move out compared to customers with One Year Contracts and Two Year Contracts.
1. **Senior Citizens vs. Churn:** Most senior citizens churn.
1. **Payment Method vs. Churn:** The majority of customers who moved out were using Electronic Checks as their payment method.
1. **Paperless Billing vs. Churn:** Customers with Paperless Billing are more likely to churn.
1. **Tech Support vs. Churn:** Customers with no Tech Support are more likely to switch to another service provider.
1. **Device Protection vs. Churn:** Customers without device protection are more likely to churn.
1. **Online Security vs. Churn:** Most customers churn in the absence of online security.
1. ` `**Internet Service vs. Churn:** Customers who use Fiber optic internet service have a higher churn rate.
1. ` `**Tenure vs. Churn:** New customers are more likely to churn.
1. ` `**Churn vs. Monthly Charges:** A higher % of customers churn when the monthly charges are high.
1. ` `**Churn vs. Total Charges:**  It seems that there is higer churn when the total charges are lower.

1. **Correlation of Churn with other variables :** 
- Month-to-month contracts, absence of online security and tech support seem to be positively correlated with churn. While, tenure, two-year contracts seem to be negatively correlated with churn.

- services such as Long-term contracts, Subscriptions without internet service, and customers engaged for 5+ years.

- Factors like Gender, Availability of PhoneService and multiple lines have alomost NO impact on Churn.


**Conclusion:**

Based on the analysis, several key findings have emerged:

1. **Demographics:** Gender, senior citizen status, and having dependents do not appear to be strong indicators of churn. However, customers without partners are more likely to churn.
1. **Customer Account Information:** Tenure and contract type play significant roles in predicting churn. Customers with shorter tenures, especially those on month-to-month contracts, are more likely to churn. In contrast, customers with longer-term contracts, such as one-year or two-year contracts, tend to stay.
1. **Customer Service Information:** Several factors related to customer services significantly impact churn. Customers without tech support, online security, or device protection are more likely to leave. Fiber optic internet service, electronic check payment methods, and paperless billing are associated with higher churn rates.
1. **Correlation:** Month-to-month contracts, absence of online security and tech support, and higher monthly charges are positively correlated with churn. Conversely, long-term contracts, tenure, and two-year contracts are negatively correlated with churn.

**To Reduce Churn:**

1. **Improve Customer Service:** Focus on enhancing customer service by offering tech support, online security, and device protection. Ensure that these services are easily accessible and valuable to customers.
1. **Contract Incentives:** Encourage customers to opt for longer-term contracts by offering incentives like discounted rates, additional services, or loyalty rewards. This can reduce churn among customers on month-to-month contracts.
1. **Address Fiber Optic Concerns:** Investigate the reasons behind the high churn rate among fiber optic internet service users. If it's related to service quality or pricing, consider adjustments to retain these customers.
1. **Payment Options:** Provide alternative payment methods that are more convenient and secure than electronic checks. Offering a variety of payment options can reduce churn among customers using electronic checks.
1. **Promote Paperless Billing Benefits:** Educate customers about the benefits of paperless billing, such as convenience and environmental impact. Encourage more customers to switch to paperless billing to reduce churn.
1. **Customer Retention Programs:** Implement customer retention programs that target high-risk segments identified in the analysis. These programs could include special offers, discounts, or personalized communication to keep customers engaged.
1. **Regular Feedback:** Continuously collect customer feedback to identify pain points and areas of improvement. Addressing customer concerns promptly can enhance loyalty and reduce churn.

By implementing these strategies based on the project findings, the telecom company can reduce churn, improve customer retention, and ultimately achieve higher customer satisfaction and profitability.





