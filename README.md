# FUTURE_DS_02
Customer Retention &amp; Churn Analysis
Customer Churn Analysis
1. Project Objective

The objective of this study was to analyze customer churn behavior, identify high-risk customer segments, evaluate customer lifetime patterns, and determine key drivers influencing retention.

2. Data Cleaning & Preparation

The dataset was preprocessed to ensure consistency and analytical reliability.

Cleaning Steps Performed:
Removed duplicate observations using customerID
Checked for missing values across all features
Converted TotalCharges from text to numeric format
Standardized categorical variables (Yes/No encoding consistency)
Created tenure-based customer cohorts
Verified data types for all variables
Retained original dataset integrity by performing transformations in separate columns
Feature Engineering:

Created:

Tenure Cohorts

Cohort	Definition
C1	0–12 months
C2	13–24 months
C3	25–48 months
C4	49–72 months
3. Dataset Summary
Metric	Value
Total Customers (N)	7043
Churned Customers	1869
Retained Customers	5174
Churn Rate	26.54%
Retention Rate	73.46%

Churn Rate Formula:
Churn \ Rate = \frac{Churned \ Customers}{Total \ Customers}\times100


4. Key Trends
Trend 1: Customer Lifecycle Effect
Tenure Group	Churn Trend
0–12 Months	Highest
13–24 Months	Moderate
25–48 Months	Lower
49–72 Months	Lowest
Observation:
Churn probability decreases as customer tenure increases.

Trend 2: Contract Dependency
Contract Type	Churn Trend
Month-to-Month	High
One Year	Moderate
Two Year	Low

Observation:

Long-term contractual commitment improves retention.

Trend 3: Service Engagement

Customers without:

Technical Support
Online Security
Add-on Services

showed higher churn concentration.

Trend 4: Pricing Sensitivity

Higher monthly charges correlate positively with churn.

5. Customer Lifetime Patterns

Average customer lifetime characteristics:

Variable	Retained	Churned
Average Tenure	Higher	Lower
Monthly Charges	Lower	Higher
Total Charges	Higher	Lower

Interpretation:

Customers leaving early contribute lower cumulative value.
6. High-Risk Customer Segments

High churn concentration observed within:

Segment	Risk Level
New Customers (0–12 months)	Very High
Month-to-Month Contracts	High
Electronic Check Users	High
Fiber Customers	High
Customers Without Support	High
7. Key Retention Drivers

Retention was positively influenced by:

Variable	Retention Impact
Long-Term Contracts	Strong
Technical Support	Positive
Online Security	Positive
Automatic Payments	Positive
Longer Tenure	Strong
8. Churn Drivers

Primary drivers identified:

Major contributors:

High monthly pricing
Low contractual commitment
Limited support services
Low service engagement
Early customer lifecycle exits
9. Key Recommendations
R1: Improve Early Lifecycle Retention

Enhanced onboarding
Customer follow-up campaigns
Usage support programs
R2: Increase Contract Commitment

Actions:

Long-term contract incentives
Loyalty rewards

Expected Effect:

R3: Increase Service Adoption

Promote:

Technical support packages
Security services
Bundled offerings
R4: Reduce Payment Friction

Actions:

Encourage automatic payments
Reduce dependency on electronic checks
10. Conclusion

Key findings indicate:

Customer churn is highest during early lifecycle stages.
Contract duration strongly influences retention.
Support services reduce churn probability.
Pricing and engagement significantly affect customer behavior.
