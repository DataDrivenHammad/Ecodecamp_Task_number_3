# Ecodecamp_Task_number_3
To create a good descriptive README for your customer churn analysis project, here’s a template based on what you've shared:


# Customer Churn Analysis Project

## Overview
This project aims to analyze customer churn behavior using a real-world dataset. The primary objective was to identify the factors contributing to customer churn and develop visualizations to better understand the underlying patterns.

**Churn** refers to when a customer stops using a company's products or services. In this analysis, various customer data points were examined, including monthly charges, daytime mins, and customer service interactions, to determine correlations with churn behavior.

## Project Objective
The key goals of this analysis were:
- To explore and understand the features that lead to customer churn.
- To visualize relationships between key variables such as Overage Fee, Day Minutes, and Customer Service Calls.
- To identify potential predictors for churn using data exploration techniques and correlation analysis.

## Data
The dataset used for this analysis contains information about:
- **CustomerServiceCalls**: Number of interactions with customer service.
- **DayMinutes**: The total number of minutes used by customers during the day.
- **OverageFee**: Additional fees incurred by customers beyond their allotted usage.
- **MonthlyCharge**: The total amount billed to customers on a monthly basis.
- **Churn**: Whether the customer has churned (binary variable).
- **AccountWeeks**: How long the customer has been with the company. 
- **DataPlan**: Whether customer is suscribed to dataplan or not.
- **ContractRenewal**: Whether customer has renewed it's contract or not.
- **DataUsage**: How much data each customer has used.
- **daycalls**: No. of calls made in a day
- **RoamMins**: Inernational calls made.
  
## Key Findings
### 1. **Customer Service Calls and Churn**
   - Customers who made more customer service calls were more likely to churn.
   - The analysis showed significant differences between the number of calls for those who churned vs. those who stayed.

### 2. **Overage Fee and Day Minutes**
   - Statistical tests performed proved that customers who churned tended to have higher overage fees compared to those who did not churn. For daymins The output indicated that there's a strong link between the number of daytime minutes a customer uses and their likelihood of churning.


### 3. **Monthly Charges and Churn**
   - There was a noticeable difference in monthly charges between customers who churned and those who did not, with higher charges correlating with higher churn rates.

## Visualizations
- **Box Plots**: Used to compare distributions of key variables such as Customer Service Calls and Monthly Charges by churn.
- **Scatter Plots**: Explored the relationship between Overage Fee, Day Minutes, and Customer Service Calls.
- **Kernel Density Estimation (KDE)**: Visualized distributions of numerical features based on churn.

## Tools and Libraries Used
- **Python**: The primary programming language used.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib & Seaborn**: For data visualization and creating plots.
- **NumPy**: For numerical operations.
- **Scikit-learn**: Used for further exploration and potential predictive modeling.

## Conclusion
The project identified several important factors that influence customer churn. Customers with high interaction with customer service, high monthly charges, and higher overage fees were more likely to churn. These insights can help in developing strategies to reduce churn by targeting high-risk customers with improved services and tailored offers.
