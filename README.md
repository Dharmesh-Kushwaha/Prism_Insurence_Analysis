# Insurance-Dashboard

## Problem Statement

This dashboard helps Prism Insurance Pvt. Ltd. analyze their overall insurance operations, customer claims, and customer feedback.
It provides a comprehensive view of policy performance, claims, coverage, and customer sentiment analysis.
The insights from the dashboard allow the company to identify profitable policy types, track claim settlement efficiency, and understand customer satisfaction levels to improve services.

### Key objectives of this dashboard:

Track Premium, Coverage, and Claim Amounts.

Understand policy distribution by type and activity (Active/Inactive).

Monitor claims by status and customer age groups.

Collect customer sentiment from feedback and identify areas of improvement.

### Steps Followed

Step 1 : Loaded the dataset (InsuranceData and CustomerFeedback) into Power BI Desktop.

Step 2 : Used Power Query Editor to clean and transform the data, enabled column distribution, column quality, and column profiling.

Step 3 : Created relationships between datasets using common keys like CustomerID and PolicyNumber.

Step 4 : Built measures for:

Total Premium Amount

Total Coverage Amount

Total Claim Amount

Count of Policies (Active/Inactive)

Step 5 : Designed card visuals for key KPIs (Premium, Coverage, Claim amounts).

Step 6 : Used bar charts to display Premium Amount by Policy Type and Claims by Status.

Step 7 : Created a donut chart to represent Active vs Inactive Policies.

Step 8 : Built a line and area chart for Claim Amount by Age Group.

Step 9 : Added a detailed table visual showing Pending, Rejected, and Settled claim values by Policy Type.

Step 10 : For Customer Analysis page:

Created a Word Cloud from customer feedback.

Used sentiment scores to rank feedback as Excellent, Good, or Needs Improvement.

Displayed customer feedback in a table with sentiment score.

Created a bar chart showing Count of Customers by Feedback Category.

Step 11 : Applied consistent dark theme visuals for a professional look.

Step 12 : Published the report to Power BI Service.

# Snapshot of Dashboard

## Insurance Overview Page
<img width="1383" height="855" alt="Image" src="https://github.com/user-attachments/assets/d467bc1b-5f3b-42cc-ab83-3de54f80b7dc" />

## Customer Analysis Page
<img width="1382" height="857" alt="Image" src="https://github.com/user-attachments/assets/545e5c87-65aa-48be-bb1c-077f8f83526d" />

# Insights

From the dashboard, the following insights can be drawn:

### [1] Policy Distribution

Total Premium Amount = 5.97M

Total Coverage Amount = 600.33M

Total Claim Amount = 16.90M

Active Policies = 58% (5.81K)

Inactive Policies = 42% (4.19K)

### [2] Premium by Policy Type

Travel insurance contributes the highest premium (2.5M).

Health and Auto policies also form a significant share.

Life and Home policies have the lowest premium contribution.

### [3] Claims Analysis

Claims by Status:

Rejected – 4.4K (highest)

Settled – 3.4K

Pending – 2.3K

Claim Amount by Age Group:

Adults have the highest claim amount (8.8M).

Elders – 6.4M

Young Adults – 1.7M

### [4] Financial Breakdown (by Policy Type & Claim Status)

Travel insurance has the highest overall claim value across Pending, Rejected, and Settled.

Auto and Health policies also have significant pending and rejected claim amounts.

Home insurance has the lowest settled amount.

### [5] Customer Sentiment Insights

### Feedback distribution:

Excellent – 54 customers

Needs Improvement – 39 customers

Good – 4 customers

Word cloud shows common keywords: very, service, policy, satisfied, process, happy.

Positive sentiment reflects satisfaction with coverage and service.

Negative feedback highlights issues like billing errors, high premiums, unclear policy terms.

### Conclusion

The dashboard provides a 360° view of Prism Insurance Pvt. Ltd.’s performance.

Business Insight: Travel policies are the most profitable, but also have high claims.

Risk Insight: High rejection rate indicates potential gaps in claim processing or documentation.

Customer Insight: While a majority of customers gave excellent feedback, a significant portion needs improvement—especially in billing clarity and policy explanations.

This dashboard enables management to take data-driven decisions for improving policy offerings, reducing claim rejections, and enhancing customer satisfaction.
