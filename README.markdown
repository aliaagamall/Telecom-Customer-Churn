# Telecom Customer Churn Analysis

This project analyzes customer churn for Meven, a fictional telecom company, using Power BI. The goal is to understand why customers leave (churn rate: 27%), why they join (join rate: 6%), and how to keep them. I used data from 7,000 customers to find patterns in demographics, services, billing, offers, and churn reasons, and provided recommendations to reduce churn.

## Project Contents

- **Telecom Customer Churn.pbix**: The Power BI file with the full analysis, including visuals (charts, maps, slicers) and measures (e.g., Churn Rate, Join Rate).
- **Customer Churn Analysis Report.pdf**: A detailed report with insights and recommendations based on the analysis.
- **Data/**: A folder containing the dataset files (e.g., Customer Churn.csv, Zip Code Population.csv) used in the analysis.

## Key Insights

- **High Churn Rate (27%)**: 1,890 customers left, especially in San Diego (64.91% churn).
- **Low Join Rate (6%)**: Only 420 new customers, mostly younger ones (10-19 years: 11.81% join rate).
- **Demographics**: Older customers (80+: 43.94% churn) and singles (32.96% churn) leave more. Married customers (19.66% churn) are more loyal.
- **Services**: Customers with add-ons like Device Protection Plan (22.50% churn) stay more than those without (39.13% churn).
- **Billing**: High-paying customers ($73.35/month) churn more. Credit Card users (14% churn) are more loyal than Mailed Check users (37% churn).
- **Offers & Contracts**: Offer E (52.92% churn) and Month-to-Month contracts (46% churn) drive churn. Offer A (6.73% churn) and Two Year contracts (3% churn) work best.
- **Churn Reasons**: Competitors (841 customers) are the top reason, driven by better devices (313) and offers (311). Dissatisfaction (321) and attitude issues (314) also matter.

## How to Use

1. **Open Power BI File**:

   - Download `Telecom Customer Churn.pbix`.
   - Open in Power BI Desktop (requires Power BI Desktop installed).
   - Explore the pages: Overview, Demographics, Services, Billing, and Churn Reasons.

2. **View Report**:

   - Open `Customer Churn Analysis Report.pdf` for a summary of insights and recommendations.

3. **Data**:

   - The `Data` folder has the raw datasets. Load them into Power BI if you want to rebuild the analysis.