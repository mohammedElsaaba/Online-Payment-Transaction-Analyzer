# Online Payment Transaction Analysis

## Project Overview
This project provides a comprehensive analysis of online payment transactions through data visualizations. It aims to identify trends, detect issues, and provide actionable insights into transaction behavior across regions, devices, and payment methods. Key metrics such as transaction counts, revenue, device types, and payment method success/failure rates are explored to optimize the payment system. The full report is available in the [Wallet Transaction Report PDF](wallet_transaction_report_project.pdf).

## Dashboard Preview
Below is a screenshot of the dashboard visualizing the transaction data:

![Dashboard Screenshot](dashboard_screenshot1.png)
![Dashboard Screenshot](dashboard_screenshot2.png)

## Data Description
The dataset includes records of online payment transactions with the following details:
- **Transaction Status**: Success or failure of each transaction.
- **Payment Method**: The method used (e.g., credit card, digital wallet).
- **Transaction Device**: The type of device (e.g., mobile, desktop).
- **Region**: The geographical region of the transaction.
- **Transaction Value**: The monetary value of transactions.
- **Transaction Fees**: Fees associated with successful transactions.

The data spans a specific time period, with monthly trends analyzed to uncover patterns and anomalies.

## Visualizations
The project employs multiple chart types to visualize the transaction data, as detailed in the [report](wallet_transaction_report_project.pdf):

1. **Cards**:
   - Display aggregate metrics such as total transactions, total revenue, and other key figures for a quick overview.

2. **Pie Charts**:
   - **Region Contribution**: Shows the percentage of transactions per region.
   - **Device Type Contribution**: Illustrates the distribution of devices used for transactions (e.g., mobile vs. desktop).

3. **Clustered Column Chart**:
   - Visualizes the revenue from successful transactions, reflecting the financial outcome of the payment system.

4. **Combo Chart (Clustered Column + Trend Line)**:
   - Displays the total transaction value over time, with a trend line highlighting a notable decrease in August.

5. **Bar Charts**:
   - Represent the transaction status (success/failure) for each payment method.
   - Enable identification of the most used methods and those with high failure rates.

6. **Donut Chart**:
   - Shows the percentage of failed transactions by region.
   - Paired with a Card to display revenue or profit from transaction fees.

## Key Insights
The analysis, detailed in the [report](wallet_transaction_report_project.pdf), uncovers critical findings:
- **Transaction Value Drop**: A significant decrease in transaction value occurred in August, as shown in the Combo Chart.
- **Payment Method Issues**: Bar Charts highlight payment methods with high failure rates, suggesting areas for improvement.
- **Regional Performance**: The Donut Chart identifies regions with higher failure rates, warranting further investigation.
- **Device Distribution**: The Pie Chart reveals the proportion of devices used, aiding in platform-specific optimizations.

   
## Dependencies
To interact with the project, you’ll need:
- **PDF Viewer**: To view the [report](./docs/wallet_transaction_report_project.pdf).
- **Visualization Tools**: Excel, Power BI, or Tableau for analysis reproduction.
