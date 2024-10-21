<div align="center">
  
# Customer Risk Analysis <img src="https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/assets/74038190/0b335028-1d3d-4ee5-b5b3-a373d499be7e" width="40">


# <img src="https://user-images.githubusercontent.com/74038190/213844263-a8897a51-32f4-4b3b-b5c2-e1528b89f6f3.png" width="50px" /> &nbsp; Power BI Dashboard &nbsp; <img src="https://user-images.githubusercontent.com/74038190/213844263-a8897a51-32f4-4b3b-b5c2-e1528b89f6f3.png" width="50px" />

![CR-Analysis](https://github.com/user-attachments/assets/009eb9db-2c64-476d-9585-f55349db6278)

</div>

## Project Overview

This project focuses on customer retention analysis for a telecom company. The objective is to identify at-risk customers and provide actionable insights through a Power BI dashboard. The dashboard is designed to help the Retention Manager and the management team visualize key metrics and understand customer churn, leading to more proactive retention strategies.

### Background Information

The Retention Manager of the telecom company requested a detailed dashboard on customer retention after being impressed by earlier work. The following key challenges and objectives were outlined in the project:

- Customers in the telecom industry are hard-earned, and losing them impacts the business significantly.
- The retention department's primary responsibility is to win back customers who have terminated their contracts.
- Current outreach is reactive (after termination). It would be more effective to identify customers at risk of churning in advance.
- Prior customer analysis using Excel ended up being inconclusive and insufficient.
- The Retention Manager wants a clear, self-explanatory visualization for the management team to act on.

## Task Objective

I was asked to:

1. Define appropriate Key Performance Indicators (KPIs) for customer retention.
2. Develop a Power BI dashboard that reflects these KPIs, providing useful insights for the Retention Manager and management.

## KPIs Defined

The following KPIs were identified and displayed on the dashboard:

- **Tech Tickets**: Number of technical support tickets raised by customers.
- **Admin Tickets**: Number of administrative support tickets raised by customers.
- **Churn Rate (%)**: Percentage of customers who have churned.
- **Total Churn**: The total number of customers who have churned.
  
## Dashboard Features

The dashboard provides various interactive visuals and filters to allow users to drill down into specific metrics. The following tasks and features were implemented:

1. **Interactive Filters**: 
    - Filters for contract type (Month-to-month, One year, Two year).
    - Filters for churn status (Yes or No).
    - Filters for Internet Service type (DSL, Fiber optic, No internet).
    - Tenure-based slider to filter customers based on their tenure with the company.
    
2. **Visuals**: 
    - **Tech and Admin Tickets**: Card visuals that highlight the number of tech and admin tickets.
    - **Churn Rate and Total Churn**: Key metrics visualized as cards for an at-a-glance view of churn statistics.
    - **Churn by Internet Service**: Bar chart showing how churn varies across different internet service types.
    - **Years of Contract**: Bar chart that breaks down the churn rate by the length of the customer's contract.
    - **Churn by Payment Method**: A combination of bar and line chart to display churn rates and sum of monthly charges, segmented by payment methods.
    - **Customer Count by Internet Service**: A donut chart that shows the distribution of customers across different internet services.
    - **Sum of Monthly Charges**: Another donut chart to visualize the distribution of monthly charges across different customer groups.
    
3. **Churn Analysis**: 
    - Visualizations that allow the Retention Manager to see at-risk customers based on their contract type, payment method, and tenure.
    - Insights into which customer groups (e.g., by contract type, internet service) are most at risk of churn.
    - A clear representation of how payment methods (e.g., electronic check, mailed check, bank transfer) correlate with customer churn rates.

## Insights Delivered

- **High Churn Rate for Month-to-Month Contracts**: The majority of churn occurs among customers on month-to-month contracts.
- **Churn is More Common with Fiber Optic Customers**: Customers using fiber optic internet services have a higher churn rate compared to those using DSL or no internet.
- **Electronic Check Payment Method is Risky**: Customers paying via electronic check show a much higher churn rate than those using other payment methods, such as credit cards or bank transfers.
- **Shorter Tenure Customers Churn More**: Customers who have been with the company for shorter durations are more likely to churn.

## How I Built the Dashboard

1. **Data Preparation**: I prepared and cleaned the dataset using Power Query in Power BI, ensuring the fields and columns were correctly structured for analysis.
   
2. **KPIs and Visual Selection**: Based on the retention manager's requirements, I identified and defined the most relevant KPIs, such as churn rate, ticket counts, and payment method trends. I selected visuals like bar charts, donut charts, and cards to best present the data.

3. **Dashboard Design**: I used Power BI's drag-and-drop interface to design a user-friendly and clean dashboard layout. The layout includes a variety of filter options and interactive visuals for easy exploration of the data by the management team.

4. **Performance Optimization**: I ensured that the dashboard performed efficiently, with quick load times even when multiple filters are applied.

## Conclusion <img src="https://user-images.githubusercontent.com/74038190/214644152-52f47eb3-5e31-4f47-8758-05c9468d5596.gif" width="25">

This Power BI dashboard equips the Retention Manager and the telecom company’s management team with the necessary tools to identify at-risk customers and devise proactive strategies to retain them. The dashboard is intuitive and visually appealing, providing clear insights into customer churn trends.
